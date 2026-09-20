<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1hw4meoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f1hw4meoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:search-property-outline" /></template>
