<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p--98q1tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p--98q1tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:star-fill" /></template>
