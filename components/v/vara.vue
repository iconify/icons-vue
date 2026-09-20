<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o7e_70_vm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vara" /></template>
<style>
.o7e_70_vm {
  fill: var(--svg-color--00ffc4, #00ffc4);
  fill-rule: evenodd;
  d: path("M12 3a9 9 0 1 1 0 18a9 9 0 0 1 0-18m.127 4.5l2.241 3.326V7.5h1.583v9.015h-2.374L7.5 7.5h1.584l5.284 7.84v-2.165L10.543 7.5z");
}

</style>
