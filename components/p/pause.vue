<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4v-78_ko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4v-78_ko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:pause" /></template>
