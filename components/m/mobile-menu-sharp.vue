<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygbe8vbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-menu-sharp" /></template>
<style>
.ygbe8vbux {
  fill: currentColor;
  d: path("M8 21.789q-.31 0-.54-.23t-.23-.54t.23-.54t.54-.229t.54.23t.23.54t-.23.539t-.54.23m3.46-.23q-.23-.23-.23-.54t.23-.54q.23-.229.54-.229t.54.23t.23.54t-.23.539t-.54.23t-.54-.23m4 0q-.23-.23-.23-.54t.23-.54q.23-.229.54-.229t.54.23t.23.54t-.23.539t-.54.23t-.54-.23M12.587 6.086q.22-.222.22-.549t-.22-.547q-.223-.22-.55-.22t-.548.22q-.22.222-.22.55t.222.547t.549.22t.548-.22M6.808 18V2h10.384v3.723h.731v2.9h-.73V18z");
}

</style>
