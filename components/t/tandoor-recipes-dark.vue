<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txyc7sgll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="txyc7sgll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tandoor-recipes-dark" /></template>
