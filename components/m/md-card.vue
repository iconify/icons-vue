<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2hji3bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z2hji3bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-card" /></template>
