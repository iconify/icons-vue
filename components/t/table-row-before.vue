<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxn-5sbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="cxn-5sbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:table-row-before" /></template>
