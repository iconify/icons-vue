<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co08zrbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="co08zrbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square" /></template>
