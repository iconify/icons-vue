<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awv-u-rtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awv-u-rtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:toggle-left-solid" /></template>
