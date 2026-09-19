<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjz4e5uiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjz4e5uiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:monitor" /></template>
