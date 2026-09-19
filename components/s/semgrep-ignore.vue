<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbh9_3bgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cbh9_3bgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:semgrep-ignore" /></template>
