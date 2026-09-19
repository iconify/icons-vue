<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lffz6_2ef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lffz6_2ef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:view-boards" /></template>
