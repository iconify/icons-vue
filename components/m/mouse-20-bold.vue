<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqm22dloe.css';
import '../../css/q/qdyabyskt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rqm22dloe"/><path class="qdyabyskt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mouse-20-bold" /></template>
