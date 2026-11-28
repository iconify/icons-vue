<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-dqlw80v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-dqlw80v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:rocket-check" /></template>
