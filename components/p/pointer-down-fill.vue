<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-q3jxbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v-q3jxbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:pointer-down-fill" /></template>
