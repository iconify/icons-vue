<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxf4odbtj.css';
import '../../css/k/k17ecxb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxf4odbtj"/><path class="k17ecxb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rename-filled" /></template>
