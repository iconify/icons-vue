<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y12mmacdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y12mmacdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:panels-left-bottom-filled" /></template>
