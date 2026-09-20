<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4q0ycbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4q0ycbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vivint" /></template>
