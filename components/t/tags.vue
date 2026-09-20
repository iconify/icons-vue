<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7qkocbig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7qkocbig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:tags" /></template>
