<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy9u6_k-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy9u6_k-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shield-check-gloss" /></template>
