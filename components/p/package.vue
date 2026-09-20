<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq2ubbcfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hq2ubbcfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:package" /></template>
