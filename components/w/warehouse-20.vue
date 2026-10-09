<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmf8y5bqk.css';
import '../../css/w/wt80nmbhx.css';
import '../../css/s/sfceoobcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wmf8y5bqk"/><path class="wt80nmbhx"/><path class="sfceoobcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:warehouse-20" /></template>
