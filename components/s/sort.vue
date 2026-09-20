<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgq2-68dl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgq2-68dl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:sort" /></template>
