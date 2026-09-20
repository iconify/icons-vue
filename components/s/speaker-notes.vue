<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2f5llbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speaker-notes" /></template>
<style>
.k2f5llbbp {
  fill: currentColor;
  d: path("M7.693 13.309q.23-.23.23-.54t-.23-.54t-.54-.229t-.538.23t-.23.54t.23.539t.539.23t.54-.23m0-2.77q.229-.23.229-.539t-.23-.54t-.54-.23t-.538.23t-.23.54t.23.54t.539.23t.54-.23m0-2.77q.229-.23.229-.54q0-.309-.23-.539t-.54-.23t-.538.23q-.23.23-.23.54t.23.54q.23.229.539.229t.54-.23m2.537 5.5H14.5v-1h-4.27zm0-2.77H17.5v-1h-7.27zm0-2.77H17.5v-1h-7.27zM3 20.078V4.616q0-.691.463-1.153T4.615 3h14.77q.69 0 1.152.463T21 4.616v10.769q0 .69-.463 1.153T19.385 17H6.077z");
}

</style>
