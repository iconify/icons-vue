<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc_wrmb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tc_wrmb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:white-flag" /></template>
