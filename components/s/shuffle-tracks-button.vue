<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="nhqdtbc2j"/><path class="u3iu-xp3u"/><path class="e889rxf0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:shuffle-tracks-button" /></template>
<style>
.e889rxf0b {
  fill: var(--svg-color--fff, #fff);
  d: path("M30.2 11L23 5v12zm0 14L23 19v12z");
}

.nhqdtbc2j {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.953 15.717c.549-1.394 1.234-2.861 2.175-4.142C13.95 10.064 12.351 9 10 9H7v4h3c1.307 0 2.119.896 2.953 2.717m6.527 5.424c-.478 1.314-1.059 2.777-1.852 4.132C18.718 26.318 20.117 27 22 27h3v-4h-3c-1.082 0-1.822-.62-2.52-1.859");
}

.u3iu-xp3u {
  fill: var(--svg-color--fff, #fff);
  d: path("M10 27H7v-4h3c1.884 0 2.739-1.816 4.117-5.673C15.441 13.617 17.09 9 22 9h3v4h-3c-1.885 0-2.739 1.817-4.117 5.673C16.559 22.383 14.91 27 10 27");
}

.x-kz1kb7j {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
