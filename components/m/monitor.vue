<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi0yuo35w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fi0yuo35w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:monitor" /></template>
