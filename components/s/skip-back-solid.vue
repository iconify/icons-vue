<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9vw5s0cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9vw5s0cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:skip-back-solid" /></template>
