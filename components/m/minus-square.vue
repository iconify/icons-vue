<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxk-8juiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxk-8juiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:minus-square" /></template>
