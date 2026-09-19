<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-u-z0bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="b-u-z0bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:safety-certificate-fill" /></template>
