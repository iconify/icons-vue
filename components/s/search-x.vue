<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx4v7zazs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mx4v7zazs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:search-x" /></template>
