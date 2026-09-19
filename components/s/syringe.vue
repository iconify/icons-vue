<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6e4nk4sv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6e4nk4sv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:syringe" /></template>
