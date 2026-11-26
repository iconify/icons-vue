<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8vxyhb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="y8vxyhb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:rectangle-horizontal" /></template>
