<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no77hrbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="no77hrbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:trash" /></template>
