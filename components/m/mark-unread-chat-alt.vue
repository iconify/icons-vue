<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffz5f3bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mark-unread-chat-alt" /></template>
<style>
.ffz5f3bmh {
  fill: currentColor;
  d: path("M17.23 5.73Q16.5 5 16.5 3.963t.73-1.77t1.77-.73t1.77.73t.73 1.77t-.73 1.769t-1.77.73t-1.77-.73M3 20.077V4.616q0-.691.463-1.153T4.615 3H14.6q-.061.25-.071.49t-.006.51q.029.729.235 1.354t.55 1.146H6.5v1h9.942q.495.462 1.161.712t1.397.25q.512 0 1.027-.125T21 7.962v7.423q0 .69-.462 1.153T19.385 17H6.077zM6.5 10.5h11v-1h-11zm0 3h7v-1h-7z");
}

</style>
