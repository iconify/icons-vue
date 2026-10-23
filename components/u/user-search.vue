<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1ra4ravg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1ra4ravg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:user-search" /></template>
