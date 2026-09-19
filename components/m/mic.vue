<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5lbg1shr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="j5lbg1shr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:mic" /></template>
