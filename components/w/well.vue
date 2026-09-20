<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9e7hmbvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="v9e7hmbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:well" /></template>
