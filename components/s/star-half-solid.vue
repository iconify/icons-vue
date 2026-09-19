<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5wb2qbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i5wb2qbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:star-half-solid" /></template>
