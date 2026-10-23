<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq-59rbmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yq-59rbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:shield-alert" /></template>
