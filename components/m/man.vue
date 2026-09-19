<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajgcukb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ajgcukb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:man" /></template>
