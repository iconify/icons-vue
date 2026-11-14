<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vdua6l_9x"/><path class="b0k9vnbke"/><path class="wcle0vb8k"/><path class="xy-ro8bys"/><path class="xtuaobc8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:skull-bold-duotone" /></template>
<style>
.b0k9vnbke {
  fill: currentColor;
  d: path("M10.6699 18.75C11.0841 18.75 11.4199 19.0858 11.4199 19.5V22H9.91992V19.5C9.91992 19.0858 10.2557 18.75 10.6699 18.75Z");
}

.vdua6l_9x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 18C5 16.8 3 13.8 3 10.5C3 5.8 7 2 12 2C17 2 21 5.8 21 10.5C21 13.8 19 16.8 16 18V19.8C16 20.8371 16 21.3556 15.6778 21.6778C15.3556 22 14.8371 22 13.8 22H10.2C9.1629 22 8.6444 22 8.3222 21.6778C8 21.3556 8 20.8371 8 19.8V18Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.wcle0vb8k {
  fill: currentColor;
  d: path("M13.3301 18.75C13.7443 18.75 14.0801 19.0858 14.0801 19.5V22H12.5801V19.5C12.5801 19.0858 12.9159 18.75 13.3301 18.75Z");
}

.xtuaobc8l {
  fill: currentColor;
  d: path("M15.5 9C16.6046 9 17.5 9.8954 17.5 11C17.5 12.1046 16.6046 13 15.5 13C14.3954 13 13.5 12.1046 13.5 11C13.5 9.8954 14.3954 9 15.5 9Z");
}

.xy-ro8bys {
  fill: currentColor;
  d: path("M8.5 9C9.6046 9 10.5 9.8954 10.5 11C10.5 12.1046 9.6046 13 8.5 13C7.3954 13 6.5 12.1046 6.5 11C6.5 9.8954 7.3954 9 8.5 9Z");
}

</style>
