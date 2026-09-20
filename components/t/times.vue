<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3s1a1w6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3s1a1w6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:times" /></template>
