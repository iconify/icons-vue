<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vgz6b35js"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:watch-fill" /></template>
<style>
.vgz6b35js {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.0999 5.1382L7.3982 2.7519C7.5233 1.7511 8.3741 1 9.3828 1L14.6172 1C15.6259 1 16.4767 1.7511 16.6018 2.7519L16.9001 5.1382C18.1498 5.5313 19 6.6899 19 8L19 16C19 17.3101 18.1498 18.4687 16.9001 18.8618L16.6018 21.2481C16.4767 22.2489 15.6259 23 14.6172 23L9.3828 23C8.3741 23 7.5233 22.2489 7.3982 21.2481L7.0999 18.8618C5.8502 18.4687 5 17.3101 5 16L5 8C5 6.6899 5.8502 5.5313 7.0999 5.1382ZM9.1328 5L14.8672 5L14.6172 3L9.3828 3L9.1328 5ZM14.8672 19L9.1328 19L9.3828 21L14.6172 21L14.8672 19Z");
}

</style>
