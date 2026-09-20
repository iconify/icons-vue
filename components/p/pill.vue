<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ittf-hbzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ittf-hbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:pill" /></template>
