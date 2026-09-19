<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-3iuhfng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-3iuhfng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:seedling-outline" /></template>
