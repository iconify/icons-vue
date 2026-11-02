<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vf6l4fvyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-basket-fill" /></template>
<style>
.vf6l4fvyo {
  fill: currentColor;
  d: path("M3 9h1.465l3.703-5.555a1 1 0 0 1 1.664 1.11L6.869 9h10.262l-2.963-4.445a1 1 0 0 1 1.664-1.11L19.535 9H21a1 1 0 0 1 0 2h-.219l-1.811 7.243c-.178.713-.52 1.382-1.043 1.905c-.511.511-1.195.852-1.927.852H8c-.732 0-1.416-.341-1.927-.852c-.523-.523-.865-1.192-1.043-1.905L3.219 11H3a1 1 0 0 1 0-2m8 8v-4a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0m4 0v-4a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0");
}

</style>
