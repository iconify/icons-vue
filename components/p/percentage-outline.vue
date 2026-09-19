<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hydl6x73v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hydl6x73v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:percentage-outline" /></template>
