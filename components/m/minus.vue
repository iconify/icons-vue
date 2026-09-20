<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g67zuo57x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g67zuo57x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:minus" /></template>
