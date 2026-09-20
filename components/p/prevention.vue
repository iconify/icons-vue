<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2dwhp-fq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2dwhp-fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:prevention" /></template>
