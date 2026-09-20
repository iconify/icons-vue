<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_bixxwoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_bixxwoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:setapp" /></template>
