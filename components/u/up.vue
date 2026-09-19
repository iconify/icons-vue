<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5yo40bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":7};
const content = `<path class="o5yo40bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:up" /></template>
