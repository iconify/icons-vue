<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/m/m1lt5n8tk.css';
import '../../css/c/cq-p70qeo.css';
import '../../css/c/cr86h_b7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="m1lt5n8tk"/><path class="cq-p70qeo"/><path class="cr86h_b7s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:turn-off-bluetooth" /></template>
