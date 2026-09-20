<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgt-5pbmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgt-5pbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:tally-three-solid" /></template>
