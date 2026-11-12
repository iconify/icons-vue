<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t4z7qo_ir"/><path class="aygw_60rm"/><path clip-rule="evenodd" class="qy2alob5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifer-zoom-out-bold-duotone" /></template>
<style>
.aygw_60rm {
  fill: currentColor;
  d: path("M11.157 20.313a9.157 9.157 0 1 0 0-18.313a9.157 9.157 0 0 0 0 18.313");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.qy2alob5l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.023 11.157c0-.4.324-.723.723-.723h4.82a.723.723 0 1 1 0 1.445h-4.82a.723.723 0 0 1-.723-.723");
}

.t4z7qo_ir {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.82 19.7c-.09-1.094.816-2.008 1.9-1.918c.189.016.414.085.643.154l.067.02l.06.018c.21.064.42.127.58.213a1.786 1.786 0 0 1 .637 2.549c-.1.152-.255.308-.41.464l-.045.045l-.044.045c-.155.157-.31.313-.46.414a1.754 1.754 0 0 1-2.527-.643c-.086-.161-.148-.373-.211-.585l-.018-.06l-.02-.068c-.07-.231-.137-.458-.152-.648");
}

</style>
