<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy6mme2wu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="uy6mme2wu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squarey" /></template>
