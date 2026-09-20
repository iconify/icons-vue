<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w05qhqb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w05qhqb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mail-send-line" /></template>
