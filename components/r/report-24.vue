<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2tkw6wrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2tkw6wrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:report-24" /></template>
