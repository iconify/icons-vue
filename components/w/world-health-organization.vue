<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3kd-rbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3kd-rbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:world-health-organization" /></template>
