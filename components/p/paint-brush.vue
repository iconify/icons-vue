<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-u7i6rxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-u7i6rxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:paint-brush" /></template>
