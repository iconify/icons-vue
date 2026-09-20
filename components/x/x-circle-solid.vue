<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dghvwbkaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dghvwbkaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:x-circle-solid" /></template>
