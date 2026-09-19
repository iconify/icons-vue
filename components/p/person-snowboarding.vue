<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy9vtw7wx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="yy9vtw7wx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:person-snowboarding" /></template>
