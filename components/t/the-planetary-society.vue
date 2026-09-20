<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1vpt6b7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1vpt6b7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:the-planetary-society" /></template>
