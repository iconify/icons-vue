<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqfaw-b_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqfaw-b_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:shield-plus" /></template>
