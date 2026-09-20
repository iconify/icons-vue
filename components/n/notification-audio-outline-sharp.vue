<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsfqywbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:notification-audio-outline-sharp" /></template>
<style>
.dsfqywbmh {
  fill: currentColor;
  d: path("M11.997 21.385q-.668 0-1.14-.475q-.472-.474-.472-1.14h3.23q0 .67-.475 1.143q-.476.472-1.143.472M5 18.769v-1h1.616V9.846q0-1.96 1.24-3.447T11 4.546V3h2v1.552q.556.106 1.062.317t.942.504l-.16.088l-.35.196q-.19.108-.35.195l-.16.088q-.451-.232-.952-.356q-.5-.122-1.032-.122q-1.823 0-3.104 1.28t-1.28 3.104v7.923h8.769v-2.792h1v2.792H19v1zm11.442-6.153V7.384h.885v5.23zm-2.326-1.308V8.692H15v2.616zm4.653 0V8.692h.885v2.616z");
}

</style>
