<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isdhl6lzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isdhl6lzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:watch" /></template>
