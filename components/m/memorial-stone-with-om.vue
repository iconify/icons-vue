<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3qqxcb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c3qqxcb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:memorial-stone-with-om" /></template>
