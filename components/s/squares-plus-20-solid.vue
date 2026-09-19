<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7iwjlcxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v7iwjlcxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:squares-plus-20-solid" /></template>
