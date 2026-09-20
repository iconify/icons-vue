<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_d16i0-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_d16i0-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:pencil" /></template>
