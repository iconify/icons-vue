<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbcbwabkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbcbwabkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sort-by-down-02" /></template>
