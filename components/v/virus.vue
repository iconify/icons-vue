<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzz5m-bbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="gzz5m-bbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:virus" /></template>
