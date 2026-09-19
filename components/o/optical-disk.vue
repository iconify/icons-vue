<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="o84it3bmf"/><g class="n1mjunbsu"><circle class="axb4q_bdx"/><path class="n0i4d5bxt"/></g><path class="qw0um2bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:optical-disk" /></template>
<style>
.axb4q_bdx {
  cx: 32px;
  cy: 32px;
  r: 6.6px;
}

.n0i4d5bxt {
  d: path("m32.2 42.6l9.2 13.6c6.8-2.6 12.2-8 14.8-14.8l-13.6-9.2c-.1 5.7-4.7 10.3-10.4 10.4m-.4-21.2L22.6 7.8c-6.8 2.6-12.2 8-14.8 14.8l13.6 9.2c.1-5.7 4.7-10.3 10.4-10.4");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.o84it3bmf {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--d0d0d0, #d0d0d0);
}

.qw0um2bxf {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M32 45c-7.1 0-13-5.8-13-13c0-7.1 5.8-13 13-13c7.1 0 13 5.8 13 13c0 7.1-5.9 13-13 13m0-23.3c-5.7 0-10.3 4.6-10.3 10.3S26.3 42.3 32 42.3S42.3 37.7 42.3 32S37.7 21.7 32 21.7");
}

</style>
