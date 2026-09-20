<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na-pm8via.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="na-pm8via"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:number-16" /></template>
