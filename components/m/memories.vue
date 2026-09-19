<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy7uvjurt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="cy7uvjurt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:memories" /></template>
