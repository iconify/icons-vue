<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-lixpbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-hand-outline-sharp" /></template>
<style>
.t-lixpbnq {
  fill: currentColor;
  d: path("M6 20V4zm9.502 2.02q-.535 0-1.023-.206q-.488-.205-.817-.622l-4.781-6.03l1.111-1.054l5.085 2.19V7.019H16.5l3.5 3.5v8q0 1.458-1.021 2.479T16.5 22.019zM5 21V3h11.077v4.02h-1V4H6v16h6.698l.81 1zm6.078-13.922q.23-.23.23-.54T11.078 6t-.54-.23T10 6t-.23.54q0 .309.23.539t.54.23t.539-.23m4.443 13.941h.979q1.037 0 1.768-.728q.732-.73.732-1.772v-7.561l-2.73-2.731h-.193v9.61l-5.723-2.464l4.007 5.104q.208.271.514.407t.646.135");
}

</style>
