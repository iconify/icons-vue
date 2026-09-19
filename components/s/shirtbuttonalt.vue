<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhdr0xjnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zhdr0xjnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:shirtbuttonalt" /></template>
