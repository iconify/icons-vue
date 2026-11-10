<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzl4vb94z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rzl4vb94z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:slice" /></template>
