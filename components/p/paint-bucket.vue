<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef0e3zb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef0e3zb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:paint-bucket" /></template>
