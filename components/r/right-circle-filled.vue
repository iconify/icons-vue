<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofj_3-bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ofj_3-bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:right-circle-filled" /></template>
