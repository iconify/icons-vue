<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6l-sicok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h6l-sicok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:octagon-outline" /></template>
