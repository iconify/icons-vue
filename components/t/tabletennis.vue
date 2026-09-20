<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkrje0bnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="wkrje0bnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:tabletennis" /></template>
