<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wry-w1bxn.css';
import '../../css/n/nyurgsbqe.css';
import '../../css/d/djgk4x_3w.css';
import '../../css/z/z16su76ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="wry-w1bxn"/><rect class="nyurgsbqe"/><rect class="djgk4x_3w"/><rect class="z16su76ar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:stats-chart-outline" /></template>
