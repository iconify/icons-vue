<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlyst4b4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="jlyst4b4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:person-crop-circle-fill-badge-minus" /></template>
