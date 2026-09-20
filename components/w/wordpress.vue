<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nillri43z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nillri43z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:wordpress" /></template>
