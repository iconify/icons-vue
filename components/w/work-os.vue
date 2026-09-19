<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk6x0-gcj.css';
import '../../css/j/jw9a98ysj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk6x0-gcj"/><path class="jw9a98ysj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:work-os" /></template>
