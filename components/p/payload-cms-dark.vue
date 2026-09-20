<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/peby3jb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="peby3jb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:payload-cms-dark" /></template>
