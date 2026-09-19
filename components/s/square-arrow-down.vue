<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6pg4ekhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="f6pg4ekhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-arrow-down" /></template>
