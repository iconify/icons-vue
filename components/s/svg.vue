<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpls246js.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gpls246js"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:svg" /></template>
