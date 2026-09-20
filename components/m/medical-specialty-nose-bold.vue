<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3dkirz7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3dkirz7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:medical-specialty-nose-bold" /></template>
