<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i28_uy10g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="i28_uy10g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:percent" /></template>
