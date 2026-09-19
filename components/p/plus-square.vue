<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eszujkbip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="eszujkbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:plus-square" /></template>
