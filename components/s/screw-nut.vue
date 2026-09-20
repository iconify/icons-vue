<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu21_9btv.css';
import '../../css/y/ygivrbbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hu21_9btv"/><path class="ygivrbbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:screw-nut" /></template>
