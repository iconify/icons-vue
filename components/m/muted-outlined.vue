<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw27-ebul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pw27-ebul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:muted-outlined" /></template>
