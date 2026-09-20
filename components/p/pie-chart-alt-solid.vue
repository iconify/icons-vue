<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueaxwlb4u.css';
import '../../css/f/fosgzfbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ueaxwlb4u"/><path class="fosgzfbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:pie-chart-alt-solid" /></template>
