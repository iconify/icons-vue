<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa7tb9a1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fa7tb9a1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:snippets-library-dark" /></template>
