<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7dkymbhs.css';
import '../../css/s/sa1-qxbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i7dkymbhs"/><path class="sa1-qxbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:paper-mill-20" /></template>
