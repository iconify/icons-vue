<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm3_ilbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm3_ilbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:sun" /></template>
