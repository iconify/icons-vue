<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="o-qy4obno"/><path class="qbt0geqhz"/><path class="p9ewazbsj"/><path class="eqe4p1b0c"/><path class="r3oi8xtju"/><path class="q2wg1eb2z"/><path class="yrp0dwbqc"/><path class="uofhf5bej"/><path class="bfmup_zwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:videocassette" /></template>
<style>
.bfmup_zwz {
  d: path("M34 26a1 1 0 0 1-1 1H3a1 1 0 1 1 0-2h30a1 1 0 0 1 1 1");
}

.eqe4p1b0c {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M28 17a3 3 0 0 0-3-3v6a3 3 0 0 0 3-3");
}

.o-qy4obno {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M36 25s0 4-4 4H4s-4 0-4-4V10c0-4 4-4 4-4h28s4 0 4 4z");
}

.p9ewazbsj {
  d: path("M29.894 12H26s-1 0-1 1v1a3 3 0 0 1 0 6v1s0 1 1 1h3.895A6.97 6.97 0 0 0 32 17a6.98 6.98 0 0 0-2.106-5");
}

.q2wg1eb2z {
  d: path("M11 20a3 3 0 1 1 0-6v-1c0-1-1-1-1-1H6.106C4.808 13.271 4 15.04 4 17s.808 3.729 2.106 5H10c1 0 1-1 1-1z");
}

.qbt0geqhz {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M32 12h-6s-1 0-1 1v8s0 1 1 1h6c1 0 2-2 2-5s-1-5-2-5");
}

.r3oi8xtju {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M4 12h6s1 0 1 1v8s0 1-1 1H4c-1 0-2-2-2-5s1-5 2-5");
}

.uofhf5bej {
  fill: var(--svg-color--88c9f9, #88c9f9);
  d: path("M13 14s0-1 1-1h8s1 0 1 1v6s0 1-1 1h-8s-1 0-1-1z");
}

.yrp0dwbqc {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M8 17a3 3 0 0 0 3 3v-6a3 3 0 0 0-3 3");
}

</style>
