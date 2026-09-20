<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crw1kccel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crw1kccel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:qwen-dark" /></template>
