<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7h67eb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q7h67eb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:search-diacritics" /></template>
