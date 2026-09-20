<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqq1feb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqq1feb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:receive-square4-filled" /></template>
