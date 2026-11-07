<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eipxycc0p.css';
import '../../css/l/lvp3cpbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eipxycc0p"/><path class="lvp3cpbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-underline-bold" /></template>
