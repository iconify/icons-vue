<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxcye_7gu"/><path class="jnekwubgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-account-balance" /></template>
<style>
.bxcye_7gu {
  fill: currentColor;
  d: path("m6.29 6l5.21-2.74L16.71 6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.jnekwubgk {
  fill: currentColor;
  d: path("M6.5 10h-2v7h2zm6 0h-2v7h2zm8.5 9H2v2h19zm-2.5-9h-2v7h2zm-7-9L2 6v2h19V6zM6.29 6l5.21-2.74L16.71 6z");
}

</style>
