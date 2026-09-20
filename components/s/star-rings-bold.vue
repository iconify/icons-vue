<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djylembry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="djylembry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-rings-bold" /></template>
