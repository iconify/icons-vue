<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h23i9q6my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1760};
const content = `<path class="h23i9q6my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:male" /></template>
