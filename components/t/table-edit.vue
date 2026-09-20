<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f08bbtbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f08bbtbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-edit" /></template>
