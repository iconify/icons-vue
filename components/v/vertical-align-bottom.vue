<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnl0g-byb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bnl0g-byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:vertical-align-bottom" /></template>
