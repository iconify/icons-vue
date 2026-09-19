<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_yw8fb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="y_yw8fb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:pencil" /></template>
