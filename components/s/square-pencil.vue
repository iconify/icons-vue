<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj2o2qrzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="nj2o2qrzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-pencil" /></template>
