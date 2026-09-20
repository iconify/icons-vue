<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osquvkb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="osquvkb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:spyglass" /></template>
