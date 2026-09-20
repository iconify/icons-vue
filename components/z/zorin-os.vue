<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":227};
const content = `<path class="o820ooped"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:zorin-os" /></template>
<style>
.o820ooped {
  fill: var(--svg-color--0af, #0af);
  d: path("M125.928 0L64.159.034l-17.884 31.35h163.553L192.15.205zM24.143 70.28L0 112.91l22.493 39.964h8.684l122.746-82.593zm199.51 0L100.89 152.875h132.686L256 113.254l-24.178-42.973zM44.47 191.773l19.398 34.186l66.205.207l61.786-.035l19.604-34.358z");
}

</style>
