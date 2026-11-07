<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4ba7dbhr.css';
import '../../css/m/mo2l0vb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o4ba7dbhr"/><path class="mo2l0vb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:transmission-bold" /></template>
