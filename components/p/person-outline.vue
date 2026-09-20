<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql33l8pgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql33l8pgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:person-outline" /></template>
