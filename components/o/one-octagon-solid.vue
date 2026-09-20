<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc7erx8nu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc7erx8nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:one-octagon-solid" /></template>
