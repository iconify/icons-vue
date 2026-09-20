<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puno4n5gf.css';
import '../../css/u/ufakx9rlh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":511.875,"height":511.824};
const content = `<path class="puno4n5gf"/><path class="ufakx9rlh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:racket" /></template>
