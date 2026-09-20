<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7c3h9bnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u7c3h9bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:safari-outline" /></template>
