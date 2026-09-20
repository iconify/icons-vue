<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp0dxhuxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sp0dxhuxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:measure-outline" /></template>
