<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj0kccuzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="cj0kccuzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:triangle-down" /></template>
