<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6i7a1tli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s6i7a1tli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:netflix-filled" /></template>
