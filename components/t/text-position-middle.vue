<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6p3nbbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6p3nbbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:text-position-middle" /></template>
