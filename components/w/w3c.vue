<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm7holb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="dm7holb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:w3c" /></template>
