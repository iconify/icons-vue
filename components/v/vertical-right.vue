<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m41stubtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="m41stubtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:vertical-right" /></template>
