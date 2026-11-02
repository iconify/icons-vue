<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vno5ecccu"/><path class="qsc21acxq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-sparkle-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qsc21acxq {
  d: path("M2 3a1 1 0 0 1 1-1h4a1 1 0 0 1 0 2H4v3a1 1 0 0 1-2 0Zm19-1a1 1 0 0 1 1 1v4a1 1 0 0 1-2 0V4h-3a1 1 0 0 1 0-2ZM11 7a1 1 0 0 1 2 0c0 1.07.311 2.146 1.082 2.918c.348.348.771.613 1.23.789A4.7 4.7 0 0 0 17 11a1 1 0 0 1 0 2c-.574 0-1.151.086-1.688.293a3.5 3.5 0 0 0-1.23.789a3.5 3.5 0 0 0-.789 1.23A4.7 4.7 0 0 0 13 17a1 1 0 0 1-2 0c0-.574-.086-1.151-.293-1.688a3.5 3.5 0 0 0-.789-1.23C9.146 13.311 8.07 13 7 13a1 1 0 0 1 0-2c2.444 0 4-1.556 4-4M3 22a1 1 0 0 1-1-1v-4a1 1 0 0 1 2 0v3h3a1 1 0 0 1 0 2Zm19-1a1 1 0 0 1-1 1h-4a1 1 0 0 1 0-2h3v-3a1 1 0 0 1 2 0Z");
}

.vno5ecccu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 6a1 1 0 0 1 1 1c0 .574.086 1.151.293 1.688c.176.459.441.882.789 1.23s.771.613 1.23.789A4.7 4.7 0 0 0 17 11a1 1 0 0 1 0 2c-.574 0-1.151.086-1.688.293a3.5 3.5 0 0 0-1.23.789a3.5 3.5 0 0 0-.789 1.23A4.7 4.7 0 0 0 13 17a1 1 0 0 1-2 0c0-.574-.086-1.151-.293-1.688a3.5 3.5 0 0 0-.789-1.23a3.5 3.5 0 0 0-1.23-.789A4.7 4.7 0 0 0 7 13a1 1 0 0 1 0-2c.574 0 1.151-.086 1.688-.293a3.5 3.5 0 0 0 1.23-.789c.348-.348.613-.771.789-1.23A4.7 4.7 0 0 0 11 7a1 1 0 0 1 1-1m0 4.519A5.4 5.4 0 0 1 10.519 12A5.4 5.4 0 0 1 12 13.481A5.4 5.4 0 0 1 13.481 12A5.4 5.4 0 0 1 12 10.519");
}

</style>
