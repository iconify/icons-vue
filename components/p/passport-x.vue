<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8d9ur5rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8d9ur5rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:passport-x" /></template>
