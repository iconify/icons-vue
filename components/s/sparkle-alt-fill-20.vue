<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz8-9gwgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cz8-9gwgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:sparkle-alt-fill-20" /></template>
