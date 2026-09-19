<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fud2otu-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fud2otu-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:switcher-outlined" /></template>
