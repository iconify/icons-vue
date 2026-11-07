<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6vyhu-he.css';
import '../../css/g/g_7c-1vki.css';
import '../../css/g/g97e8sbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6vyhu-he"/><path class="g_7c-1vki"/><path class="g97e8sbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sofa-2-bold" /></template>
