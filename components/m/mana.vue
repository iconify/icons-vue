<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm-zazo7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sm-zazo7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:mana" /></template>
