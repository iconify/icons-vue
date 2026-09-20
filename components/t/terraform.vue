<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2gxtub-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r2gxtub-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:terraform" /></template>
