<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="obgygxbfg"/><path class="gtcp0vbnn"/><path class="bazjtnx-a"/></g><path class="hl2w_eimj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:signal-high-bold-duotone" /></template>
<style>
.bazjtnx-a {
  d: path("M16.5 7.25C16.9142 7.25 17.25 7.58579 17.25 8V20C17.25 20.4142 16.9142 20.75 16.5 20.75C16.0858 20.75 15.75 20.4142 15.75 20V8C15.75 7.58579 16.0858 7.25 16.5 7.25Z");
}

.gtcp0vbnn {
  d: path("M12 11.25C12.4142 11.25 12.75 11.5858 12.75 12V20C12.75 20.4142 12.4142 20.75 12 20.75C11.5858 20.75 11.25 20.4142 11.25 20V12C11.25 11.5858 11.5858 11.25 12 11.25Z");
}

.hl2w_eimj {
  fill: currentColor;
  d: path("M3 19.25C3.41421 19.25 3.75 19.5858 3.75 20C3.75 20.4142 3.41421 20.75 3 20.75C2.58579 20.75 2.25 20.4142 2.25 20C2.25 19.5858 2.58579 19.25 3 19.25Z");
}

.obgygxbfg {
  d: path("M7.5 15.25C7.91421 15.25 8.25 15.5858 8.25 16V20C8.25 20.4142 7.91421 20.75 7.5 20.75C7.08579 20.75 6.75 20.4142 6.75 20V16C6.75 15.5858 7.08579 15.25 7.5 15.25Z");
}

.xtpeb-edw {
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
