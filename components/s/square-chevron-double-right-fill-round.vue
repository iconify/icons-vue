<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5hiwnbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5hiwnbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-chevron-double-right-fill-round" /></template>
