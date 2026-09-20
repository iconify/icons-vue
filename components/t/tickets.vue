<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce2kczbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ce2kczbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:tickets" /></template>
