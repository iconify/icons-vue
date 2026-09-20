<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slgty_bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="slgty_bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:radio-remix" /></template>
