<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxccggbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uxccggbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tandoor-recipes-light" /></template>
