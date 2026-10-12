<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v19eqwb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v19eqwb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:panels-top-left-filled" /></template>
