<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="cn9r8ov8o"/><path class="hbw6wcyei"/><path class="x51-76t_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:shield" /></template>
<style>
.cn9r8ov8o {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M33 3c-7-3-15-3-15-3S10 0 3 3C0 18 3 31 18 36c15-5 18-18 15-33");
}

.hbw6wcyei {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M18 33.884C6.412 29.729 1.961 19.831 4.76 4.444C11.063 2.029 17.928 2 18 2c.071 0 6.958.04 13.24 2.444c2.799 15.387-1.652 25.285-13.24 29.44");
}

.x51-76t_e {
  fill: var(--svg-color--269, #269);
  d: path("M31.24 4.444C24.958 2.04 18.071 2 18 2v31.884c11.588-4.155 16.039-14.053 13.24-29.44");
}

</style>
