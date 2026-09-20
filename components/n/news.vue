<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-j7qghfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-j7qghfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:news" /></template>
