<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5gq29b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5gq29b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:plus" /></template>
