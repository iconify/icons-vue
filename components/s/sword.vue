<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa1hmy53v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fa1hmy53v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:sword" /></template>
