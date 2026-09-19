<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1kiis7qb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1472};
const content = `<path class="f1kiis7qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:user-boss" /></template>
