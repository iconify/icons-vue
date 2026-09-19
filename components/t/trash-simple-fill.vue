<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuw_msbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zuw_msbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:trash-simple-fill" /></template>
