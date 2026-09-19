<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1up5se8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c1up5se8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:merge-cells" /></template>
