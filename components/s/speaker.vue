<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-li6vbct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="g-li6vbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:speaker" /></template>
