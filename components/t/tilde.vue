<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf4ba4bjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf4ba4bjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:tilde" /></template>
