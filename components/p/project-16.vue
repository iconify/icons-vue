<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxv1afqss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pxv1afqss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:project-16" /></template>
