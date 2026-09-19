<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee4nf81dg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee4nf81dg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:pencil" /></template>
