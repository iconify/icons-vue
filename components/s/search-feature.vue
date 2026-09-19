<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vij074qlg.css';
import '../../css/i/iabrmvfcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="vij074qlg"/><path class="iabrmvfcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:search-feature" /></template>
