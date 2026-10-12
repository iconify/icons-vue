<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmto18o1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmto18o1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:stretch-vertical-filled" /></template>
