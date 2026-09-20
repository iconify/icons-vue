<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-1et6bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-1et6bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:office" /></template>
