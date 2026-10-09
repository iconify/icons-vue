<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-9xc2bcj.css';
import '../../css/m/mxnl1347f.css';
import '../../css/g/g9pwdi6pr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s-9xc2bcj"/><path class="mxnl1347f"/><path class="g9pwdi6pr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:transformer-pole-20" /></template>
