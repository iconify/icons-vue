<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ols8qwbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ols8qwbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:party" /></template>
