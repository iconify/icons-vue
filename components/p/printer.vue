<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0qa3eb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="j0qa3eb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:printer" /></template>
