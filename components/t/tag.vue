<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr9ra2vab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr9ra2vab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:tag" /></template>
