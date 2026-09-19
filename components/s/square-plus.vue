<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd2k8rb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="gd2k8rb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:square-plus" /></template>
