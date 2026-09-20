<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz_z0jb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":168};
const content = `<path class="dz_z0jb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nuxt" /></template>
