<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7e5s8-6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7e5s8-6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:trash-x" /></template>
