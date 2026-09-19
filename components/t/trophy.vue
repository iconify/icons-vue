<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3lee7b8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3lee7b8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:trophy" /></template>
