<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi2gs_ofg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi2gs_ofg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:photo-filled" /></template>
