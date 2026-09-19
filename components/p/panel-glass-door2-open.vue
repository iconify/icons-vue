<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy3q7pbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy3q7pbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:panel-glass-door2-open" /></template>
