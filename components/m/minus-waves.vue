<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwxxzy0-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwxxzy0-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:minus-waves" /></template>
