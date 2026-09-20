<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j91bif6wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<path class="j91bif6wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:switch-left-f" /></template>
