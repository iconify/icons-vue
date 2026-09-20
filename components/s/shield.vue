<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf3o9ac6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cf3o9ac6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:shield" /></template>
