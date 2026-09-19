<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw6ppnbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="iw6ppnbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:next" /></template>
