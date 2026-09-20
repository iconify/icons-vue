<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob-dqqbgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob-dqqbgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:smoke-detector-alert-outline" /></template>
