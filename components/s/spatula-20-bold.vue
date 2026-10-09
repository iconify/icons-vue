<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww9p1ok1f.css';
import '../../css/i/iipvbgbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ww9p1ok1f"/><path class="iipvbgbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spatula-20-bold" /></template>
