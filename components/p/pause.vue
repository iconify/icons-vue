<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzhw3vcys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzhw3vcys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:pause" /></template>
