<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op1oeqo0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op1oeqo0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:number-9-bulk-round" /></template>
