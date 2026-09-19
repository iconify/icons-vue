<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/najqe30yb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="najqe30yb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:star-half-outline" /></template>
