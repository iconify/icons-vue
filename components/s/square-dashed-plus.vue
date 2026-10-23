<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t53b2rntw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t53b2rntw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square-dashed-plus" /></template>
