<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krn8lyatz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="krn8lyatz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:person" /></template>
