<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo2aetewc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:notification-audio-off-outline" /></template>
<style>
.yo2aetewc {
  fill: currentColor;
  d: path("M16.442 12.616V7.385h.885v5.23zm-2.326-1.308V8.692H15v2.616zm4.653 0V8.692h.885v2.616zM5 18.769v-1h1.616V9.846q0-.575.125-1.156q.126-.582.378-1.11l.77.77q-.137.363-.205.737t-.068.76v7.922h8.353L2.67 4.546l.708-.707l17.285 17.284l-.708.708l-3.073-3.062zM9.035 6.608l-.72-.72q.558-.515 1.239-.863T11 4.546V4q0-.417.291-.708q.291-.292.707-.292t.709.292T13 4v.542q.556.116 1.062.327t.942.504l-.16.088l-.35.196l-.35.195l-.16.089q-.451-.233-.952-.356T12 5.462q-.832 0-1.6.286q-.77.287-1.366.86m2.962 14.777q-.667 0-1.14-.475q-.472-.474-.472-1.14h3.231q0 .67-.475 1.143q-.476.472-1.144.472m-.08-11.896");
}

</style>
