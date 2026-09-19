<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmfk8e0td.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vmfk8e0td"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:tiktok-small" /></template>
