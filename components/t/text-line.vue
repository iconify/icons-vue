<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywo665bia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywo665bia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:text-line" /></template>
