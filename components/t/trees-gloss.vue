<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qz_d23t2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qz_d23t2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:trees-gloss" /></template>
