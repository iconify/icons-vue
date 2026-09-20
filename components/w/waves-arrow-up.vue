<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub1plsr2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ub1plsr2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:waves-arrow-up" /></template>
