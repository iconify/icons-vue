<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spo-uibbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="spo-uibbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:triangle-down-16" /></template>
