<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsp17zbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsp17zbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:skateboarding-fill" /></template>
