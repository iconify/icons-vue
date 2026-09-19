<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elxqqdbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elxqqdbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:tailwind-solid" /></template>
