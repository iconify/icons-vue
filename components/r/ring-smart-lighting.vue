<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er6g1acjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er6g1acjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ring-smart-lighting" /></template>
