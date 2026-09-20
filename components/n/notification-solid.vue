<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua9nt7b1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ua9nt7b1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:notification-solid" /></template>
