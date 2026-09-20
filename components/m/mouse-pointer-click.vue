<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6y3pjc9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6y3pjc9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mouse-pointer-click" /></template>
