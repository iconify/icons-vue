<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0jjviyol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n0jjviyol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:salt" /></template>
