<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxjmkrb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="yxjmkrb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:text-style" /></template>
