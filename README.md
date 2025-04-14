# BodyTracking Sync

**BodyTracking Sync** é um app de body tracking em tempo real feito com .NET MAUI e TensorFlow MoveNet.  
Ele utiliza a câmera do dispositivo Android para capturar poses humanas e sincronizar os dados com personagens 3D no Blender.

## ✨ Recursos
- Captura de poses em tempo real com MoveNet (TensorFlow Lite).
- Envio de dados para o Blender via WebSocket ou JSON.
- Compatível com rigs personalizados.
- Interface leve e intuitiva.


## 🔧 Tecnologias usadas
- .NET MAUI
- TensorFlow Lite (.tflite – MoveNet)
- WebSocket
- Blender (recepção de dados via addon/script personalizado)


## 🚀 Como compilar
1. Clone o repositório:
   ```bash
   git clone https://github.com/weslleyartz/bodytracking-sync.git


## 📱 Versão paga na Play Store
A versão compilada e pronta para uso está disponível na Play Store por um valor simbólico.  
Isso ajuda a manter o projeto vivo e em constante evolução.

🔗 **[Link para a Play Store](#)**

## 🔧 Versão open source
Você pode compilar o app gratuitamente em seu próprio dispositivo Android.  
Todo o código está aberto e licenciado sob a **GPLv3**, garantindo liberdade para estudar, modificar e distribuir.

## 📜 Licença

Este projeto está licenciado sob a **GNU General Public License v3.0** – veja o arquivo [LICENSE](./LICENSE) para mais detalhes.

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se livre para abrir _issues_, enviar _pull requests_ ou propor melhorias.

---

## 📦 Modelos TensorFlow

Este projeto utiliza o modelo MoveNet (SinglePose Thunder) da Google via TensorFlow Lite.  
O modelo é licenciado sob Apache License 2.0 e está incluído neste repositório para facilitar o uso local.

🔗 [Mais informações sobre o modelo](https://www.tensorflow.org/lite/models/pose_estimation/overview)



Feito com ❤️ usando .NET MAUI + TensorFlow