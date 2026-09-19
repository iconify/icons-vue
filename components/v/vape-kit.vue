<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv42zablp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cv42zablp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:vape-kit" /></template>
