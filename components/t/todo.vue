<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsbgqs9hv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lsbgqs9hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:todo" /></template>
