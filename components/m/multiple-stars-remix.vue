<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igsg2zuyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="igsg2zuyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:multiple-stars-remix" /></template>
