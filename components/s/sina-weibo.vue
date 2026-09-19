<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr7325j1p.css';
import '../../css/v/vix1e0hxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wr7325j1p"/><path class="vix1e0hxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:sina-weibo" /></template>
