<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/niueucb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="niueucb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:velo" /></template>
