<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp471zbxk.css';
import '../../css/z/z53wpybvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yp471zbxk"/><path class="z53wpybvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:virus" /></template>
