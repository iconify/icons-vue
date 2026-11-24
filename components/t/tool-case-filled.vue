<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmnbjnb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nmnbjnb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tool-case-filled" /></template>
