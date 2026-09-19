<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4vpd_lgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="r4vpd_lgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:twitter-square-filled" /></template>
