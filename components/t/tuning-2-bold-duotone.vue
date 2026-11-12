<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m03pku77p"/><path class="q7wq8kbpw"/><g class="xtpeb-edw"><path class="rmfkw9bns"/><path class="bh4awnbzk"/><path class="ro_trobcb"/><path class="ikzl0k6ol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tuning-2-bold-duotone" /></template>
<style>
.bh4awnbzk {
  d: path("M11.3555 6.2085C11.2867 6.46064 11.25 6.72602 11.25 6.99997C11.25 7.24405 11.2791 7.48132 11.3342 7.7085L1.75 7.7085C1.33579 7.7085 1 7.37271 1 6.9585C1 6.54428 1.33579 6.2085 1.75 6.2085H11.3555Z");
}

.ikzl0k6ol {
  d: path("M12.1658 17.7085H21.75C22.1642 17.7085 22.5 17.3727 22.5 16.9585C22.5 16.5443 22.1642 16.2085 21.75 16.2085H12.1445C12.2133 16.4606 12.25 16.726 12.25 17C12.25 17.2441 12.2209 17.4813 12.1658 17.7085Z");
}

.m03pku77p {
  fill: currentColor;
  d: path("M9.25 14C10.9069 14 12.25 15.3431 12.25 17C12.25 18.6569 10.9069 20 9.25 20C7.59315 20 6.25 18.6569 6.25 17C6.25 15.3431 7.59315 14 9.25 14Z");
}

.q7wq8kbpw {
  fill: currentColor;
  d: path("M14.25 4C12.5931 4 11.25 5.34315 11.25 7C11.25 8.65685 12.5931 10 14.25 10C15.9069 10 17.25 8.65685 17.25 7C17.25 5.34315 15.9069 4 14.25 4Z");
}

.rmfkw9bns {
  d: path("M17.1658 7.7085C17.2208 7.48132 17.25 7.24405 17.25 6.99997C17.25 6.72602 17.2133 6.46064 17.1445 6.2085H21.75C22.1642 6.2085 22.5 6.54428 22.5 6.9585C22.5 7.37271 22.1642 7.7085 21.75 7.7085L17.1658 7.7085Z");
}

.ro_trobcb {
  d: path("M6.35551 16.2085H1.75C1.33579 16.2085 1 16.5443 1 16.9585C1 17.3727 1.33579 17.7085 1.75 17.7085H6.33416C6.27915 17.4813 6.25 17.2441 6.25 17C6.25 16.726 6.28672 16.4606 6.35551 16.2085Z");
}

.xtpeb-edw {
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
