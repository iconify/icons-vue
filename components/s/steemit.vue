<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td5yvf_el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td5yvf_el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:steemit" /></template>
