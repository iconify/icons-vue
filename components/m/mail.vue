<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7j8yz-sj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7j8yz-sj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:mail" /></template>
