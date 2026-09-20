<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1t7cdk1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h1t7cdk1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stars-2-outline" /></template>
