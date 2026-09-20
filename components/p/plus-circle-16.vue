<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dicd2ghbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dicd2ghbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:plus-circle-16" /></template>
