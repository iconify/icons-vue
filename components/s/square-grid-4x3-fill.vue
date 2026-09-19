<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/biwamf8aq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="biwamf8aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-grid-4x3-fill" /></template>
