<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uy7o13brg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mark-unread-chat-alt-sharp" /></template>
<style>
.uy7o13brg {
  fill: currentColor;
  d: path("M17.23 5.733q-.73-.728-.73-1.77t.729-1.77t1.769-.731t1.771.728t.731 1.77t-.728 1.77t-1.77.732t-1.771-.729M3 20.077V3h11.6q-.061.25-.071.49t-.006.51q.029.729.235 1.354t.55 1.146H6.5v1h9.942q.495.462 1.161.712t1.397.25q.512 0 1.027-.125T21 7.962V17H6.077zM6.5 10.5h11v-1h-11zm0 3h7v-1h-7z");
}

</style>
