<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0zh-5cub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0zh-5cub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:printer-alert" /></template>
