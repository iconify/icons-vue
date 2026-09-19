<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akko4peii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="akko4peii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-fill-on-square-fill" /></template>
