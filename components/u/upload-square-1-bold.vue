<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh21a-bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gh21a-bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:upload-square-1-bold" /></template>
