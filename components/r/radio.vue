<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufd3ayb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":896};
const content = `<path class="ufd3ayb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:radio" /></template>
