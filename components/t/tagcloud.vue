<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnb-2sb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cnb-2sb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:tagcloud" /></template>
