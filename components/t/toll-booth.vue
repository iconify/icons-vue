<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvlu8fesh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gvlu8fesh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:toll-booth" /></template>
