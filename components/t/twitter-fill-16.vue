<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu6haob4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tu6haob4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:twitter-fill-16" /></template>
