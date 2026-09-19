<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz-0r32uk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="jz-0r32uk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:suit-spade-fill" /></template>
