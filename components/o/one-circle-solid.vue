<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye3rocb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye3rocb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:one-circle-solid" /></template>
