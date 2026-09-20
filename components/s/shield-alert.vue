<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi2twwbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi2twwbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:shield-alert" /></template>
