<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x81pse-8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x81pse-8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:npm-solid" /></template>
