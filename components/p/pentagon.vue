<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azi51ub6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azi51ub6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:pentagon" /></template>
