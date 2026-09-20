<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st267to5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="st267to5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:search-results" /></template>
