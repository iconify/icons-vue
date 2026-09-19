<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi33acb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hi33acb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:safety-certificate-outlined" /></template>
