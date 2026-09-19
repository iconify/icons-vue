<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_3i9xybj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="j_3i9xybj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:minus-slash-plus" /></template>
