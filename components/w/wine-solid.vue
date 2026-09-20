<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0y_56bux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0y_56bux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:wine-solid" /></template>
