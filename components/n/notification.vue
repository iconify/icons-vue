<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oldue7tnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oldue7tnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:notification" /></template>
