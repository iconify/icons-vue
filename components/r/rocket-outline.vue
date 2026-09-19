<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9fy5tbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9fy5tbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:rocket-outline" /></template>
