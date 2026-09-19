<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm6p6wbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gm6p6wbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:shower-filled" /></template>
