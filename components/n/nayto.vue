<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="aa2rttbat"/><path class="tulg8qbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nayto" /></template>
<style>
.aa2rttbat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.376 38.77c-2.238-11.798 4.945-5.26 11.385-3.391s11.011 1.911 16.191-.064c-.774.87-2.761 3.683-2.74 6.247c.012 1.596-3.574 3.186-3.574 3.186M17.88 13.865l-.223 5.832c-.147 3.846-9.039 5.138-9.689-.064l-.35-2.804m35.059-1.817l-.127 6.343c-.061 3.059-6.718 3.03-6.693-.351l.032-4.335m3.169-8.016l-8.875 10.152l-.16-2.773a6.75 6.75 0 0 0-1.465 4.685C22.4 17.663 18.408 12.6 19.282 3.024m-1.995.551c-1.99 2.326-3.094 5.133-2.912 6.815l-2.373-4.23M2.888 19.935a9.36 9.36 0 0 0 3.104 3.14l-3.473.012");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tulg8qbhk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.27 18.04l.01-2.607m.516-1.1c4.694-1.183 11.268-1.316 13.085-.468m24.796 1.147c-1.51-1.016-4.524-.812-6.884-.446M33.18 27.315l.031 1.306m12.219-6.345l-2.37 1.915l2.44.064");
}

</style>
