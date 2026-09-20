<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at8qoi4ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="at8qoi4ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:undo" /></template>
