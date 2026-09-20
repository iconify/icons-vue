<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptg53ibta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptg53ibta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:pause" /></template>
