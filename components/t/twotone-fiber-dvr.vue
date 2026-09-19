<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfhe35pwh"/><path class="d97x-cc2q"/><path class="nyvtiibea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-fiber-dvr" /></template>
<style>
.d97x-cc2q {
  fill: currentColor;
  d: path("M3 5h18v14H3z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.kfhe35pwh {
  fill: currentColor;
  d: path("M20 11.56v-.89c0-.76-.58-1.33-1.33-1.33h-3.11v5.33h1.33v-1.78h1.02l.76 1.78H20l-.8-1.87c.44-.22.8-.71.8-1.24m-1.33 0h-1.78v-.89h1.78zM7.11 9.33H4v5.33h3.11c.76 0 1.33-.58 1.33-1.33v-2.67c0-.75-.57-1.33-1.33-1.33m0 4H5.33v-2.67h1.78zm7-4h-1.34l-.89 3.05L11 9.33H9.66l1.56 5.34h1.33z");
}

.nyvtiibea {
  fill: currentColor;
  d: path("M21 3H3c-1.11 0-2 .89-2 2v14a2 2 0 0 0 2 2h18a2 2 0 0 0 2-2V5c0-1.11-.89-2-2-2m0 16H3V5h18z");
}

</style>
