<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j17jcdb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:print-connect-sharp" /></template>
<style>
.j17jcdb3g {
  fill: currentColor;
  d: path("m17.95 19.464l-2.138-2.114l.713-.708l1.425 1.42l3.525-3.525l.713.688zM7 20v-4H3.577V8.616h16.846v2.807q-.31-.1-.643-.165q-.334-.066-.667-.066q-1.7 0-3.114.88q-1.415.878-2.172 2.39H8V19h5.466q.078.28.203.521q.125.24.264.479zM7 7.846v-3.23h10v3.23z");
}

</style>
