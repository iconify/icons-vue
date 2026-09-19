<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-ixh8fnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":471,"height":735};
const content = `<path class="u-ixh8fnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:r-upper-case" /></template>
