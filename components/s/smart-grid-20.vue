<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyb-4v94m.css';
import '../../css/o/olexncc0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xyb-4v94m"/><path class="olexncc0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-grid-20" /></template>
