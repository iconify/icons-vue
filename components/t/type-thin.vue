<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks2-_5wjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks2-_5wjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:type-thin" /></template>
