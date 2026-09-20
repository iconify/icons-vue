<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="jpq0qub3f"/><path class="eibbtrwof"/><path class="zlsi18uor"/><circle class="si9vyheay"/><path class="h9e_9hbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:turtle" /></template>
<style>
.eibbtrwof {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M16.715 33.143c0 2.761-1.279 2.857-2.857 2.857S11 35.903 11 33.143c0-.489.085-1.029.234-1.587c.69-2.59 2.754-5.556 4.052-5.556c1.578 0 1.429 4.382 1.429 7.143m8.571 0c0 2.761 1.278 2.857 2.856 2.857C29.721 36 31 35.903 31 33.143a6.3 6.3 0 0 0-.234-1.587C30.075 28.966 28.012 26 26.714 26c-1.578 0-1.428 4.382-1.428 7.143");
}

.h9e_9hbrk {
  fill: var(--svg-color--5c913b, #5c913b);
  d: path("M23.667 25.1c0 3.591-1.418 3.9-3.167 3.9s-3.167-.31-3.167-3.9S18.75 17 20.5 17s3.167 4.51 3.167 8.1M30 24c.871 3.482-.784 4-2.533 4s-2.533.69-2.533-2.9s-1.116-6.5.633-6.5C27.315 18.6 29 20 30 24m-13.933 1.1c0 3.591-.785 2.9-2.534 2.9s-3.404-.518-2.533-4c1-4 3.251-5.4 5-5.4s.067 2.91.067 6.5");
}

.jpq0qub3f {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M9.842 19.922c0 9.842 6.575 9.673 5.158 10.078c-7 2-8.803-7.618-9.464-7.618c-2.378 0-5.536-.423-5.536-2.46C0 17.883 2.46 15 6.151 15c2.379 0 3.691 2.883 3.691 4.922M36 28.638c0 1.104-3.518-.741-5 0c-2 1-2-.896-2-2s1.343-1 3-1s4 1.895 4 3");
}

.si9vyheay {
  cx: 5px;
  cy: 18px;
  r: 1px;
  fill: var(--svg-color--292f33, #292f33);
}

.zlsi18uor {
  fill: var(--svg-color--3e721d, #3e721d);
  d: path("M32 27c0 4-5.149 4-11.5 4S9 31 9 27c0-6.627 5.149-12 11.5-12S32 20.373 32 27");
}

</style>
