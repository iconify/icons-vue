<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqnw13lvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqnw13lvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:megaphone-alt" /></template>
