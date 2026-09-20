<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="n1hdn-8hg"/><path class="pu7t1nbmv"/><path class="zpjfmxbuu"/><path class="w4b4xzlyv"/><path class="cmilo-bic"/><path class="wy5ud_-nt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:pencil" /></template>
<style>
.cmilo-bic {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("m2.183 10.517l8.335-8.335l5.208 5.209l-8.334 8.335z");
}

.n1hdn-8hg {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M35.222 33.598c-.647-2.101-1.705-6.059-2.325-7.566c-.501-1.216-.969-2.438-1.544-3.014s-1.553-.53-2.143.058c0 0-2.469 1.675-3.354 2.783c-1.108.882-2.785 3.357-2.785 3.357c-.59.59-.635 1.567-.06 2.143c.576.575 1.798 1.043 3.015 1.544c1.506.62 5.465 1.676 7.566 2.325c.359.11 1.74-1.271 1.63-1.63");
}

.pu7t1nbmv {
  fill: var(--svg-color--ea596e, #ea596e);
  d: path("M13.643 5.308a2.946 2.946 0 0 1 0 4.167l-4.167 4.168a2.95 2.95 0 0 1-4.167 0L1.141 9.475a2.95 2.95 0 0 1 0-4.167l4.167-4.167a2.946 2.946 0 0 1 4.167 0z");
}

.w4b4xzlyv {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M32.078 34.763s2.709 1.489 3.441.757s-.765-3.435-.765-3.435s-2.566.048-2.676 2.678");
}

.wy5ud_-nt {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("m3.225 11.558l8.334-8.334l1.042 1.042L4.267 12.6zm2.083 2.086l8.335-8.335l1.042 1.042l-8.335 8.334z");
}

.zpjfmxbuu {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("m31.353 23.018l-4.17 4.17l-4.163 4.165L7.392 15.726l8.335-8.334z");
}

</style>
