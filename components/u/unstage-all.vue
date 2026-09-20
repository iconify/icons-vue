<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td6ma8plu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="td6ma8plu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:unstage-all" /></template>
