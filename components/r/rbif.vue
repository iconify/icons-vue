<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4yx2dbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rbif" /></template>
<style>
.y4yx2dbce {
  fill: var(--svg-color--0095f1, #0095f1);
  d: path("M5.813 21h5.062V3H9.61c.18 4.871-.337 15.294-3.796 18m12.375 0h-5.063V3h1.266c-.18 4.871.337 15.294 3.797 18");
}

</style>
