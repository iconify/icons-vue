<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j00zp6u7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":16};
const content = `<path class="j00zp6u7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:primitive-square" /></template>
