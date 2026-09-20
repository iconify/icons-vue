<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dms_gtbfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="dms_gtbfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:triangle-down" /></template>
