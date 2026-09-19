<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnmwcn8va.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnmwcn8va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:steak-filled" /></template>
