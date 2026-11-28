<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvp6asbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvp6asbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:pill" /></template>
