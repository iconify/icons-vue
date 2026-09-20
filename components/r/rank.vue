<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzo0wjp8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzo0wjp8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rank" /></template>
