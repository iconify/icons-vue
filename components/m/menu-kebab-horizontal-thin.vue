<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_2twub0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_2twub0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:menu-kebab-horizontal-thin" /></template>
