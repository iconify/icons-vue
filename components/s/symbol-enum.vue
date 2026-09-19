<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe8xhe4fr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fe8xhe4fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:symbol-enum" /></template>
