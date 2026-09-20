<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="rs1z1zb9c"/><path class="qf36hk9_n"/><path class="eyp63-b6v"/><path class="ld85j-_nf"/><path class="azcmfi83a"/><path class="f-h6mccir"/><path class="ipmblq2-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:wedding" /></template>
<style>
.azcmfi83a {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M31.998 27a1 1 0 0 1-.495-.132l-13.504-7.717l-13.504 7.717a.999.999 0 1 1-.992-1.736l14-8a1 1 0 0 1 .992 0l14 8A.998.998 0 0 1 31.998 27m-8.999-13a1 1 0 0 1-.624-.219l-4.376-3.5l-4.374 3.5a1 1 0 0 1-1.25-1.562l4.999-4a1 1 0 0 1 1.25 0l5.001 4A1 1 0 0 1 22.999 14");
}

.eyp63-b6v {
  fill: var(--svg-color--662113, #662113);
  d: path("M19.999 15A2 2 0 0 0 16 15v7h4z");
}

.f-h6mccir {
  fill: var(--svg-color--662113, #662113);
  d: path("M12.999 31A2 2 0 1 0 9 31v5h4zm7-2A2 2 0 0 0 16 29v7h4zm7 2A2 2 0 0 0 23 31v5h4z");
}

.ipmblq2-k {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M1 6c0-2.761 3.963-4 5 0c1.121-4 5-2.761 5 0c0 3-5 6-5 6S1 9 1 6m24 0c0-2.761 3.963-4 5 0c1.121-4 5-2.761 5 0c0 3-5 6-5 6s-5-3-5-6");
}

.ld85j-_nf {
  fill: var(--svg-color--f4abba, #f4abba);
  d: path("M17.999 18L4 26v9a1 1 0 0 0 1 1h26a1 1 0 0 0 1-1v-9z");
}

.qf36hk9_n {
  fill: var(--svg-color--f4abba, #f4abba);
  d: path("m18 9l-5.143 4H13v9h10v-9h.143z");
}

.rs1z1zb9c {
  fill: var(--svg-color--bcbec0, #bcbec0);
  d: path("M20 2h-1V1a1 1 0 1 0-2 0v1h-1a1 1 0 1 0 0 2h1v6a1 1 0 1 0 2 0V4h1a1 1 0 1 0 0-2");
}

</style>
