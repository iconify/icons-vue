<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6-rb-61d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="c6-rb-61d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:next" /></template>
