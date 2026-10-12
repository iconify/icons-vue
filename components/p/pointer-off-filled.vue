<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i__nhrbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i__nhrbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:pointer-off-filled" /></template>
