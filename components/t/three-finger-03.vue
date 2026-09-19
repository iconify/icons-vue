<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8cnuve7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8cnuve7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:three-finger-03" /></template>
