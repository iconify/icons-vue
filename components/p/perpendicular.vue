<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5qb0ukzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5qb0ukzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:perpendicular" /></template>
