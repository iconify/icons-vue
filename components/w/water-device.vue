<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3wuugj7j.css';
import '../../css/t/t42cetwhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j3wuugj7j"/><path class="t42cetwhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:water-device" /></template>
