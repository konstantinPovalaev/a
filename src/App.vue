<template>
  <Container>
    <ChatWindow>
      <ChatMessage username="Ivan" time="21.12.2019 05:00:50">
        Hello, World!!!
      </ChatMessage>
    </ChatWindow>
  </Container>
</template>

<script>
import Container from "./components/Container.vue";
import ChatWindow from "./components/ChatWindow.vue";
import ChatMessage from "./components/ChatMessage.vue";

export default {
  name: "App",
  components: {
    Container,
    ChatWindow,
    ChatMessage,
  },
};
</script>

<style>
body {
  margin: 0;
  background-color: #f9f9fa;
}
</style>
