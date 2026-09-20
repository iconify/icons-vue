<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8n6gwang"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vib" /></template>
<style>
.p8n6gwang {
  fill: var(--svg-color--ff1e43, #ff1e43);
  d: path("M8.143 3H4.607l10.286 18h4.5V3h-3.214v13.822z");
}

</style>
