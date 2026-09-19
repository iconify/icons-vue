<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/docw4db7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="docw4db7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:th-list" /></template>
