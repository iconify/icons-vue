<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztzh1dyat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztzh1dyat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:mountain-peak" /></template>
