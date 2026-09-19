<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdqxufbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":39,"height":26};
const content = `<path class="pdqxufbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:wordmark-capital-the-26" /></template>
