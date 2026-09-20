<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzky8c53b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jzky8c53b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:row-houses" /></template>
