<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grlqybb5l.css';
import '../../css/q/q4-kh7ybm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="grlqybb5l"/><path class="q4-kh7ybm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:microwave-20-bold" /></template>
