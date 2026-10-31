<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghuqzibzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghuqzibzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ungroup-round" /></template>
