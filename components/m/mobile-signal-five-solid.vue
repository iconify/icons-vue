<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gde208bxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gde208bxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:mobile-signal-five-solid" /></template>
