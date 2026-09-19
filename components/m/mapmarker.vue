<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwcunacxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":770,"height":1025};
const content = `<path class="fwcunacxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:mapmarker" /></template>
