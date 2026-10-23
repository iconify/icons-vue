<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocgb-bj4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocgb-bj4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:plug-2" /></template>
