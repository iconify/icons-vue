<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/domj21oca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="domj21oca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:type-gloss" /></template>
