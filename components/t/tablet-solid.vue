<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0yccyk2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c0yccyk2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:tablet-solid" /></template>
