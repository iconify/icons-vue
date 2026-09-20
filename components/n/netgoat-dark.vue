<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv5pdontf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fv5pdontf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netgoat-dark" /></template>
