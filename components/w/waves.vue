<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzbcbub2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzbcbub2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:waves" /></template>
