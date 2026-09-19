<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6i949bga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k6i949bga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:truck-solid" /></template>
