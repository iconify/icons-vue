<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj-wp8-cg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj-wp8-cg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:shrimp-off" /></template>
