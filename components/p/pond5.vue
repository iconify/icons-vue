<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6g6lkbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6g6lkbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:pond5" /></template>
