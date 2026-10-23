<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n53_6nb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n53_6nb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mouse-pointer-2-off" /></template>
