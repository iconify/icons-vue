<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt66w7kwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt66w7kwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:syllabary-hiragana" /></template>
