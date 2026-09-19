<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw9xuwfok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="dw9xuwfok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:umbrella-fill" /></template>
