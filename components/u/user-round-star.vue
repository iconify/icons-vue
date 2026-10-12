<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v440o84zi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v440o84zi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:user-round-star" /></template>
