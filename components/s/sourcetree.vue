<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmjs13dcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bmjs13dcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:sourcetree" /></template>
