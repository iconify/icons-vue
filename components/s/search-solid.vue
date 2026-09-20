<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk-46wnbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk-46wnbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:search-solid" /></template>
