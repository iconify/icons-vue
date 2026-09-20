<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnc29jbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xnc29jbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:mouse" /></template>
