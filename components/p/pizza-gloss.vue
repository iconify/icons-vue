<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz-zvvklq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cz-zvvklq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pizza-gloss" /></template>
