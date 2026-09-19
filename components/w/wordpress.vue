<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgseyjraa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lgseyjraa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:wordpress" /></template>
