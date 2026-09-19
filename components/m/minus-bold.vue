<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze1sy3buw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ze1sy3buw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:minus-bold" /></template>
