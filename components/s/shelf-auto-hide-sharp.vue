<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ref1upjfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shelf-auto-hide-sharp" /></template>
<style>
.ref1upjfh {
  fill: currentColor;
  d: path("M12 17q.31 0 .54-.23t.23-.54t-.23-.539t-.54-.23t-.54.23t-.23.54t.23.54T12 17m-3.46-.23q.23-.23.23-.54q0-.309-.23-.539t-.54-.23t-.54.23t-.23.54t.23.54T8 17t.54-.23M16 17q.31 0 .54-.23t.23-.54t-.23-.539t-.54-.23t-.54.23t-.23.54t.23.54T16 17M4 20V4h16v16z");
}

</style>
