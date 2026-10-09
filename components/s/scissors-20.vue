<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0--pbdfi.css';
import '../../css/z/zxgl3h68t.css';
import '../../css/w/wo93-6h9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p0--pbdfi"/><path class="zxgl3h68t"/><path class="wo93-6h9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scissors-20" /></template>
