<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdg210b0m.css';
import '../../css/y/yacgnsfyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mdg210b0m"/><path class="yacgnsfyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wine-bottle-20" /></template>
