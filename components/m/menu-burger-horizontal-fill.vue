<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufvu6tbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ufvu6tbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:menu-burger-horizontal-fill" /></template>
