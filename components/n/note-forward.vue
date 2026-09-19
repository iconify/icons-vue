<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8romb68f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="o8romb68f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:note-forward" /></template>
