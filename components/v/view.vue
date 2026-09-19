<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvyzhcstg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":795,"height":614};
const content = `<path class="uvyzhcstg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:view" /></template>
