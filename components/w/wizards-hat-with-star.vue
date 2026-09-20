<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcy6asx8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hcy6asx8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wizards-hat-with-star" /></template>
