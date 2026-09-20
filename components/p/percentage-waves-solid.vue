<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dir0ivzqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dir0ivzqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:percentage-waves-solid" /></template>
