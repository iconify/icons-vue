<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="u5buzsbvy"/><path class="kkx5edbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:triangular-flag" /></template>
<style>
.kkx5edbgm {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M11 4c0-2.2 1.636-3.25 3.636-2.333l16.727 7.667c2 .917 2 2.417 0 3.333l-16.727 7.667C12.636 21.25 11 20.2 11 18z");
}

.u5buzsbvy {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M13 34s0 2-2 2s-2-2-2-2V2s0-2 2-2s2 2 2 2z");
}

</style>
