<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld4yb5bhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld4yb5bhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:panel-bottom" /></template>
