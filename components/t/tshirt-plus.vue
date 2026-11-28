<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eprk_cmdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eprk_cmdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:tshirt-plus" /></template>
