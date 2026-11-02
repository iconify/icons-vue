<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yhtzv6iob"/><path class="bf0o8pprw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:prompt-bulk-sharp" /></template>
<style>
.bf0o8pprw {
  d: path("M8 5H7v14h1a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2h1V5H4a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2m6 2a1 1 0 0 1 2 0c0 1.07.311 2.146 1.082 2.918c.348.348.771.613 1.23.789A4.7 4.7 0 0 0 20 11a1 1 0 0 1 0 2c-.574 0-1.151.086-1.688.293a3.5 3.5 0 0 0-1.23.789a3.5 3.5 0 0 0-.789 1.23A4.7 4.7 0 0 0 16 17a1 1 0 0 1-2 0c0-.574-.086-1.151-.293-1.688a3.5 3.5 0 0 0-.789-1.23C12.146 13.311 11.07 13 10 13a1 1 0 0 1 0-2c2.444 0 4-1.556 4-4");
}

.cuyn6tgcc {
  fill: currentColor;
}

.yhtzv6iob {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 6a1 1 0 0 1 1 1c0 .574.086 1.151.293 1.688c.176.459.441.882.789 1.23s.771.613 1.23.789A4.7 4.7 0 0 0 20 11a1 1 0 0 1 0 2c-.574 0-1.151.086-1.688.293a3.5 3.5 0 0 0-1.23.789a3.5 3.5 0 0 0-.789 1.23A4.7 4.7 0 0 0 16 17a1 1 0 0 1-2 0c0-.574-.086-1.151-.293-1.688a3.5 3.5 0 0 0-.789-1.23a3.5 3.5 0 0 0-1.23-.789A4.7 4.7 0 0 0 10 13a1 1 0 0 1 0-2c.574 0 1.151-.086 1.688-.293a3.5 3.5 0 0 0 1.23-.789c.348-.348.613-.771.789-1.23A4.7 4.7 0 0 0 14 7a1 1 0 0 1 1-1m0 4.519A5.4 5.4 0 0 1 13.519 12A5.4 5.4 0 0 1 15 13.481A5.4 5.4 0 0 1 16.481 12A5.4 5.4 0 0 1 15 10.519");
}

</style>
