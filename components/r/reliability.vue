<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4b12-bwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="h4b12-bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:reliability" /></template>
