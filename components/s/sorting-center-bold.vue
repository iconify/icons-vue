<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1zombcaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1zombcaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sorting-center-bold" /></template>
