<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy1-74gpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy1-74gpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:mobile-signal-four" /></template>
