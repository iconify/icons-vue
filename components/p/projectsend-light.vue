<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci49n8l4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ci49n8l4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:projectsend-light" /></template>
