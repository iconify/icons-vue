<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i06o_1-mk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:voice-chat-outline" /></template>
<style>
.i06o_1-mk {
  fill: currentColor;
  d: path("M6.308 10.5h.884v-1h-.884zm2.5 2h.884v-5h-.884zm2.75 2h.884v-9h-.884zm2.75-2h.884v-5h-.884zm2.5-2h.884v-1h-.884zM3 20.077V4.616q0-.691.463-1.153T4.615 3h14.77q.69 0 1.152.463T21 4.616v10.769q0 .69-.463 1.153T19.385 17H6.077zM5.65 16h13.735q.23 0 .423-.192t.192-.423V4.615q0-.23-.192-.423T19.385 4H4.615q-.23 0-.423.192T4 4.615v13.03zM4 16V4z");
}

</style>
