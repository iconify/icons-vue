<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0hd-6bnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="o0hd-6bnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:rectangle-vertical" /></template>
