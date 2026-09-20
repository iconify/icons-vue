<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8vyhi8lx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8vyhi8lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:trumpet" /></template>
