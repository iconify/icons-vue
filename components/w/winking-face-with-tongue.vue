<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><path class="fwv8c-bho"/><g class="fbp0m0b1e"><circle class="t0b6ykgek"/><path class="o52vk7bhe"/></g><path class="yn7ksmeol"/><path class="kze0mwblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:winking-face-with-tongue" /></template>
<style>
.fbp0m0b1e {
  fill: var(--svg-color--664e27, #664e27);
}

.fwv8c-bho {
  fill: var(--svg-color--fff, #fff);
  d: path("M31.2 24.6c0 5.5-4.5 10-10 10s-10-4.5-10-10s4.5-10 10-10c5.6 0 10 4.5 10 10");
}

.kze0mwblk {
  fill: var(--svg-color--e2596c, #e2596c);
  d: path("M33.5 44L32 57.8L30.5 44z");
}

.o52vk7bhe {
  d: path("M51 29.1C49.1 25 46.3 23 43.5 23s-5.6 2-7.5 6.1c-.2.4.8 1.2 1.3.8c1.8-1.5 4-2.1 6.2-2.1s4.4.6 6.2 2.1c.5.4 1.5-.4 1.3-.8M47.9 38H16.1c-.7 0-1.1.5-1.1 1c0 7.3 6 15 17 15s17-7.7 17-15c0-.5-.4-1-1.1-1");
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.t0b6ykgek {
  cx: 21.2px;
  cy: 24.6px;
  r: 4.5px;
}

.yn7ksmeol {
  fill: var(--svg-color--ff717f, #ff717f);
  d: path("M41.2 44H22.8c-.7 0-.8.3-.8.8v4C22 57.6 26.5 62 32 62s10-4.4 10-13.2v-4c0-.5-.1-.8-.8-.8");
}

</style>
