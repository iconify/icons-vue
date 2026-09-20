<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahd-08pqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahd-08pqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:previous2-outlined" /></template>
