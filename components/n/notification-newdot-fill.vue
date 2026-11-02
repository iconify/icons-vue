<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v31pe2msq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v31pe2msq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:notification-newdot-fill" /></template>
