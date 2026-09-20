<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h02zmjtek.css';
import '../../css/q/qy0rpabfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="h02zmjtek"/><path class="qy0rpabfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:upload" /></template>
