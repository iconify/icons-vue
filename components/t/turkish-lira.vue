<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqrg33beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pqrg33beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:turkish-lira" /></template>
