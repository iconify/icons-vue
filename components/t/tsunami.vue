<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbhel3d9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sbhel3d9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tsunami" /></template>
