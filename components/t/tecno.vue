<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5wwf8b9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":149,"height":30};
const content = `<path clip-rule="evenodd" class="r5wwf8b9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tecno" /></template>
