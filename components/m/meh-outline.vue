<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg2am7bzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lg2am7bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:meh-outline" /></template>
