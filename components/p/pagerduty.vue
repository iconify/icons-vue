<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khuc_kbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khuc_kbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:pagerduty" /></template>
