<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p92x1l1zg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="p92x1l1zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:trash" /></template>
