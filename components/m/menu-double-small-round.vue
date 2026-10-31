<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm0ne0i8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm0ne0i8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:menu-double-small-round" /></template>
