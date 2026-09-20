<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egj1p0bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="egj1p0bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:star-o" /></template>
