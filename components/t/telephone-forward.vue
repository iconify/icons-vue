<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fos3e4dkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fos3e4dkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:telephone-forward" /></template>
