<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttb64rtvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ttb64rtvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:project" /></template>
