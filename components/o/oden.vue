<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="k97fe4tcq"/><path class="a7iob0bln"/><path class="l-6rpybqe"/><path class="oyq6cccdz"/><path class="wjgg4nwbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:oden" /></template>
<style>
.a7iob0bln {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M6.729 3.046C4.077 2.51 2.467 4.213 3.151 6.83l1.843 7.055c.684 2.617 2.808 3.193 4.72 1.28l6.103-6.102c1.913-1.913 1.309-3.916-1.343-4.452z");
}

.k97fe4tcq {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M33.884 35.229c-.314 0-.629-.12-.869-.36L2.33 4.185a1.229 1.229 0 1 1 1.738-1.738l30.685 30.685a1.229 1.229 0 0 1-.869 2.097");
}

.l-6rpybqe {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M22.614 15.968a6.762 6.762 0 1 1-13.524-.002a6.762 6.762 0 0 1 13.524.002");
}

.oyq6cccdz {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M22.052 30.707c-.96.96-2.518.96-3.477 0l-3.478-3.478a2.46 2.46 0 0 1 0-3.477l8.693-8.693a2.46 2.46 0 0 1 3.478 0l3.478 3.477a2.46 2.46 0 0 1 0 3.478z");
}

.wjgg4nwbn {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M33.884 35.229c-.314 0-.629-.12-.869-.36l-9.118-9.118a1.229 1.229 0 1 1 1.738-1.738l9.118 9.118a1.229 1.229 0 0 1-.869 2.098");
}

</style>
