<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f3-5il0pr"/><path class="mzsz8ybom"/><path class="ozukpcchl"/><path class="ya2rmdq5c"/><path class="f_nygzbci"/><path class="vhygwjv3e"/><path class="i7bus3i_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:skiing-line-duotone" /></template>
<style>
.f_nygzbci {
  d: path("M19.75 5.24292C19.75 6.34752 18.8546 7.24292 17.75 7.24292C16.6454 7.24292 15.75 6.34752 15.75 5.24292C15.75 4.13832 16.6454 3.24292 17.75 3.24292C18.8546 3.24292 19.75 4.13832 19.75 5.24292Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.f3-5il0pr {
  d: path("M15.1508 8.8429L10.5508 11.6429C9.45077 12.3429 9.65077 13.7429 10.8508 14.1429L12.9508 14.8429C13.8508 15.1429 14.1508 16.0429 13.6508 16.8429L12.5508 18.1762");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i7bus3i_o {
  d: path("M2.55078 13.6429L17.5508 20.4429C19.1508 21.1429 20.6508 20.6429 21.4508 19.2429");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mzsz8ybom {
  d: path("M9.84921 13.0812L7.34961 15.8189");
}

.ozukpcchl {
  d: path("M15.1504 8.8429C16.1504 9.6429 17.1504 10.4429 18.3504 10.8429");
}

.vhygwjv3e {
  d: path("M12.75 8.78691L3.75 4.70691");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ya2rmdq5c {
  d: path("M15.1508 8.8429C14.0508 7.3429 12.9508 7.0429 11.5508 8.2429");
}

</style>
