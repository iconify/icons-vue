<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1d2zac5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t1d2zac5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:notebook" /></template>
