<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd8kj4bnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd8kj4bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:smart-home-alert" /></template>
