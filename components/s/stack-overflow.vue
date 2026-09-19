<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-jq7lsui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-jq7lsui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:stack-overflow" /></template>
