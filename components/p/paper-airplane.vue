<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_v0_v6mz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_v0_v6mz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:paper-airplane" /></template>
