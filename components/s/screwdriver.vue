<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdag2ccwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1,"top":-1};
const content = `<path class="fdag2ccwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:screwdriver" /></template>
