<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw88lzjcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw88lzjcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:search-line" /></template>
