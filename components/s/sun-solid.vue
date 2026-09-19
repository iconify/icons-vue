<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3n--xb1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f3n--xb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:sun-solid" /></template>
