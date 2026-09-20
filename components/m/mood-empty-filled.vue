<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt30kgbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt30kgbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:mood-empty-filled" /></template>
