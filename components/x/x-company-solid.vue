<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe1mwfbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe1mwfbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:x-company-solid" /></template>
