<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hooo6gbzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hooo6gbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:property-safety" /></template>
