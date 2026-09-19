<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbcepspec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bbcepspec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:offset-environmental" /></template>
