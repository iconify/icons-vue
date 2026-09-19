<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpwc0-b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gpwc0-b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:tags-outline" /></template>
