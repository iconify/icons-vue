<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s01zth5am.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1632,"height":1760};
const content = `<path class="s01zth5am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:wheelchair" /></template>
