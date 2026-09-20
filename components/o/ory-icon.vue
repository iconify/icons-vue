<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":511};
const content = `<path class="xgn5y5jik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:ory-icon" /></template>
<style>
.xgn5y5jik {
  fill: var(--svg-color--4f46e5, #4f46e5);
  d: path("M128 127.698c-70.704 0-128 57.161-128 127.698s57.296 127.698 128 127.698c70.706 0 128-57.16 128-127.698s-57.294-127.698-128-127.698M0 111.736V63.849L128 0l128 63.85v47.886l-128-63.85zm256 287.32v47.887l-128 63.85l-128-63.85v-47.886l128 63.849z");
}

</style>
