<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu4jkdj_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wu4jkdj_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:minus-square3" /></template>
