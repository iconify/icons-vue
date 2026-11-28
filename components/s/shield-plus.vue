<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0rpkn2qp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0rpkn2qp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:shield-plus" /></template>
