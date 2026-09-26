<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qr0hxdh-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mouse-fill" /></template>
<style>
.qr0hxdh-f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2C15.866 2 19 5.134 19 9L19 15C19 18.866 15.866 22 12 22C8.134 22 5 18.866 5 15L5 9C5 5.134 8.134 2 12 2ZM13 7C13 6.4477 12.5523 6 12 6C11.4477 6 11 6.4477 11 7L11 8C11 8.5523 11.4477 9 12 9C12.5523 9 13 8.5523 13 8L13 7Z");
}

</style>
