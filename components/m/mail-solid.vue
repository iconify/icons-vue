<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am_cqm3ok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am_cqm3ok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:mail-solid" /></template>
