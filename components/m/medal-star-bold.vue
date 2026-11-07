<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yccjtab6a.css';
import '../../css/c/ctt96pn4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yccjtab6a"/><path class="ctt96pn4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:medal-star-bold" /></template>
