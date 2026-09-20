<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocutishoh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":520,"height":520};
const content = `<path class="ocutishoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:matrix-light" /></template>
