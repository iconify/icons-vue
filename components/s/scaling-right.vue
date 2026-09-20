<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpoaudemz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpoaudemz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:scaling-right" /></template>
