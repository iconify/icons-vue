<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4q8gybuy.css';
import '../../css/p/pl0eixign.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a4q8gybuy"/><path class="pl0eixign"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:superscript-20-bold" /></template>
