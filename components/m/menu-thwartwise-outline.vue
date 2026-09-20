<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2qsp9-vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a2qsp9-vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:menu-thwartwise-outline" /></template>
