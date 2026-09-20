<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_af56bqu.css';
import '../../css/q/qnb3e9bul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f_af56bqu"/><path class="qnb3e9bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:school-science-bag" /></template>
