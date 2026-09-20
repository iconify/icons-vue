<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd7lvq7fq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="gd7lvq7fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:post-terms" /></template>
