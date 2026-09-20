<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypdbx5cct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-6,"top":-2};
const content = `<path class="ypdbx5cct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:mic" /></template>
