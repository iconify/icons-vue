<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz74oebap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz74oebap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rvc" /></template>
