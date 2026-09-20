<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4yrdmeaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t4yrdmeaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:stomach" /></template>
