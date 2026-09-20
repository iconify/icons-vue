<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="jus_-g5gh"/><path class="nk5vrrvax"/><path class="lhctd_b1k"/><path class="pncn6vbtc"/><ellipse class="iae1b4wcn"/><path class="o1tnd4brp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:wine-glass" /></template>
<style>
.iae1b4wcn {
  cx: 17.5px;
  cy: 9.5px;
  fill: var(--svg-color--dd2e44, #dd2e44);
  rx: 8.5px;
  ry: 1.5px;
}

.jus_-g5gh {
  fill: var(--svg-color--8899a6, #8899a6);
  d: path("M19 20.255S29.042 18.042 29.042 4.25c0-1.481-1.167-2.25-3.416-2.25H9.129C8.004 2 5.8 1.738 5.8 4.125c0 13.708 10.2 16.13 10.2 16.13v10.123s-4.584 2.34-5.498 2.883c-.984.562-.33 1.462.063 1.617c.656.258 2.253 1.102 6.78 1.102c4.641 0 6.202-.914 6.765-1.102c.217-.072 1.347-.932.011-1.723C21.743 31.747 19 30.378 19 30.378z");
}

.lhctd_b1k {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M7.458 3.583c2.042 9.5 5.458 12.792 8.699 13.835c1.11.358 2.026.428 2.801.123c3.5-1.375 7.542-5.667 8.167-13.583c.161-2.037-19.667-.375-19.667-.375");
}

.nk5vrrvax {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M29 3.442c0 1.621-3.547 2.935-11.623 2.935S5.754 5.063 5.754 3.442C5.754 1.82 9.301.507 17.377.507S29 1.821 29 3.442");
}

.o1tnd4brp {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.168 6.659c-5.03 0-8.783-1.11-9.801-1.587a1 1 0 0 1 .849-1.811c1.239.582 9.455 2.894 18.596-.127a1 1 0 1 1 .626 1.9c-3.676 1.214-7.209 1.625-10.27 1.625");
}

.pncn6vbtc {
  fill: var(--svg-color--a0041e, #a0041e);
  d: path("M9 9.5C9 13 12.333 18 17.333 18S26 12.542 26 9.542c-6 0-17-.042-17-.042");
}

</style>
