<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll8y8vutm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll8y8vutm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:user-access-control" /></template>
