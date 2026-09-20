<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzwl-lbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzwl-lbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:minus-octagon" /></template>
