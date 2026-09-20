<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvw6ufsvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dvw6ufsvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:people-and-person-pointing" /></template>
