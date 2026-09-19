<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-edk1j6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-edk1j6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:text-align-left" /></template>
