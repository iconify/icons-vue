<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="v3tcsqbdd"/><path class="hp30o6bdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:vibration-mode" /></template>
<style>
.hp30o6bdj {
  fill: var(--svg-color--fff, #fff);
  d: path("M38.4 13H25.6c-2.4 0-4.3 1.9-4.3 4.2v29.6c0 2.3 1.9 4.2 4.3 4.2h12.9c2.4 0 4.3-1.9 4.3-4.2V17.2c-.1-2.3-2-4.2-4.4-4.2m-8.5 1.5h4.2c.3 0 .5.2.5.5s-.2.5-.5.5h-4.2c-.3 0-.5-.2-.5-.5s.2-.5.5-.5M32 48.9c-.7 0-1.3-.6-1.3-1.3s.6-1.3 1.3-1.3s1.3.6 1.3 1.3s-.6 1.3-1.3 1.3m8.6-4.7H23.4v-27h17.2zM10.8 21.3c1.5 3.5 1.9 7.1 2 10.7c0 3.6-.4 7.2-2 10.7c-.3-3.5-.1-7.1-.1-10.7s-.1-7.1.1-10.7m3.8-5.3c1.8 5.2 2.3 10.7 2.4 16c-.1 5.4-.6 10.8-2.4 16c0-5.2.3-10.5.4-15.7c0-5.4-.3-10.9-.4-16.3m38.6 26.7c-1.5-3.5-1.9-7.1-2-10.7c0-3.6.4-7.2 2-10.7c.3 3.5.1 7.1.1 10.7s.1 7.1-.1 10.7M49.4 48c-1.8-5.2-2.3-10.7-2.4-16c.1-5.4.6-10.8 2.4-16c0 5.2-.3 10.5-.4 15.7c0 5.4.3 10.9.4 16.3");
}

.v3tcsqbdd {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--eda454, #eda454);
}

</style>
