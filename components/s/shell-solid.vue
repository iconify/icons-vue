<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1fub1sqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1fub1sqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:shell-solid" /></template>
