<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na9r72qao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="na9r72qao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:travel-case" /></template>
