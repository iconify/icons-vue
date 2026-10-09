<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdx1pbuzq.css';
import '../../css/d/dzwhzcc4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cdx1pbuzq"/><path class="dzwhzcc4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:relay-20-bold" /></template>
