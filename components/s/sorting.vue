<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgcju0jts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgcju0jts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:sorting" /></template>
