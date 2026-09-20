<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="qocsenbwf"/><path class="v1m5d0fzf"/><path class="ro14f9q4x"/><circle class="ywu4b9ufl"/><path class="fthwz887o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:sports-medal" /></template>
<style>
.fthwz887o {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M21.278 30.634a.7.7 0 0 1-.406-.131L18 28.444l-2.871 2.059a.697.697 0 0 1-1.071-.777l1.071-3.456l-2.845-2.005a.698.698 0 0 1 .409-1.259l3.524-.005l1.122-3.37a.697.697 0 0 1 1.324 0l1.103 3.37l3.542.005a.697.697 0 0 1 .409 1.259l-2.846 2.005l1.071 3.456a.695.695 0 0 1-.664.908");
}

.qocsenbwf {
  fill: var(--svg-color--55acee, #55acee);
  d: path("m18 8l-7-8H0l14 17l11.521-4.75z");
}

.ro14f9q4x {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M23.26 16.026c.08-.217.131-.448.131-.693a2 2 0 0 0-2-2h-6.667a2 2 0 0 0-2 2c0 .245.05.476.131.693c-3.258 1.826-5.464 5.307-5.464 9.307C7.391 31.224 12.166 36 18.058 36s10.667-4.776 10.667-10.667c-.001-4-2.206-7.481-5.465-9.307");
}

.v1m5d0fzf {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("m25 0l-7 8l5.39 7.312l1.227-1.489L36 0z");
}

.ywu4b9ufl {
  cx: 18.058px;
  cy: 25.333px;
  r: 8px;
  fill: var(--svg-color--ffd983, #ffd983);
}

</style>
