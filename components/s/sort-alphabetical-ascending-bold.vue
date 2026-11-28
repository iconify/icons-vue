<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdfu06-uh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="cdfu06-uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:sort-alphabetical-ascending-bold" /></template>
