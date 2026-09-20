<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvsgq4bmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sfp" /></template>
<style>
.tvsgq4bmx {
  fill: var(--svg-color--4b21ef, #4b21ef);
  d: path("M9.43 3.61a2.06 2.06 0 0 1 1.462-.607h10.105L16.667 7.5H8.29c-.529 0-.788.26-.788.788v7.057l-4.155-3.987a1.18 1.18 0 0 1 0-1.67zm6.281 12.89H7.333l-4.33 4.498h10.105c.55 0 1.068-.22 1.462-.607l6.084-6.079a1.18 1.18 0 0 0 0-1.67L16.5 8.654v7.057c0 .529-.26.788-.788.788");
}

</style>
