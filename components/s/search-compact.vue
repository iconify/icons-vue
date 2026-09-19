<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3q2zxbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="u3q2zxbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:search-compact" /></template>
