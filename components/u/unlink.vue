<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-alhn0sb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-alhn0sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:unlink" /></template>
