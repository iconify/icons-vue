<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="y9sl5ebrb"/><path class="hboilo6fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:mobile-phone" /></template>
<style>
.hboilo6fx {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M9 5h18v26H9z");
}

.y9sl5ebrb {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M11 36s-4 0-4-4V4s0-4 4-4h14s4 0 4 4v28s0 4-4 4z");
}

</style>
