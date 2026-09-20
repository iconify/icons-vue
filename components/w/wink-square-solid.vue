<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez5o3y60g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ez5o3y60g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:wink-square-solid" /></template>
