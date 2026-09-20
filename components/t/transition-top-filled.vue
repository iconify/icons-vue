<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbf1i-a_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbf1i-a_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:transition-top-filled" /></template>
