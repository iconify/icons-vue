<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1v2tk9wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="y1v2tk9wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:textbox" /></template>
