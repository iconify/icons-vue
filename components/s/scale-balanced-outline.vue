<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlxal_o3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlxal_o3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:scale-balanced-outline" /></template>
