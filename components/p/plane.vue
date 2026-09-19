<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfdaihttu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1408};
const content = `<path class="zfdaihttu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:plane" /></template>
