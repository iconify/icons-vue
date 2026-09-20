<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sydoq6blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sydoq6blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:showpad" /></template>
