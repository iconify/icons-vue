<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttp7_shbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ttp7_shbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:onion-roof-shape" /></template>
