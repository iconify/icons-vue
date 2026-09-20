<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng5xczucu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng5xczucu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:text-underline" /></template>
