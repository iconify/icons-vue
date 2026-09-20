<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uep2s2b1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uep2s2b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:search-dot" /></template>
