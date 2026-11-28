<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plna2dbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plna2dbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:plane-solid" /></template>
