<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp-p7zbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp-p7zbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:photocrowd" /></template>
