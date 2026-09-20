<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuu2eibco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuu2eibco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:tag2-filled" /></template>
