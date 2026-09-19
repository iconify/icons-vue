<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlkpk-77t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jlkpk-77t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:regex" /></template>
