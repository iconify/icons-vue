<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt60b7s8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt60b7s8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:share" /></template>
