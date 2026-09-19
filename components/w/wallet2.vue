<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zeow0krbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zeow0krbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:wallet2" /></template>
