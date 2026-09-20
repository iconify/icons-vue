<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9b08--1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9b08--1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:onlyoffice" /></template>
