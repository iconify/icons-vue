<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-iazk_qb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="f-iazk_qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:springer" /></template>
