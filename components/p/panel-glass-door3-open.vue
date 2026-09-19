<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f949bccnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f949bccnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:panel-glass-door3-open" /></template>
