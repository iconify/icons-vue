<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbb9tbcfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gbb9tbcfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:oven-mitts" /></template>
