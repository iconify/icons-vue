<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6vaij6_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6vaij6_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:snt" /></template>
