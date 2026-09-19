<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4jxjzb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="g4jxjzb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:photo-fill-on-rectangle-fill" /></template>
