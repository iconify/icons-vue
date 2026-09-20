<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmuay5b3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmuay5b3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:turkish-lira-solid" /></template>
