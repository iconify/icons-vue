<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c67r7smis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c67r7smis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:music-3-filled" /></template>
