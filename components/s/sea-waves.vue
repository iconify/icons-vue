<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vplra2zco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vplra2zco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:sea-waves" /></template>
