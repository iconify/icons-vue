<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilvr2qb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":300};
const content = `<path class="ilvr2qb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:ngrx-actions" /></template>
