<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp1g0tbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="dp1g0tbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:not-allowed" /></template>
