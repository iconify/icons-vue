<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4g3ob5-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1664};
const content = `<path class="c4g3ob5-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:person" /></template>
