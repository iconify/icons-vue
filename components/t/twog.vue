<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzw70nbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":832};
const content = `<path class="fzw70nbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:twog" /></template>
