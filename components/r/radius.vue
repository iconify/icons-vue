<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7vznm6oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f7vznm6oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:radius" /></template>
