<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lru3qwfcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lru3qwfcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:users-check" /></template>
