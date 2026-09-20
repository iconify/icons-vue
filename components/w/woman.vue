<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f91fo6bxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="f91fo6bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:woman" /></template>
