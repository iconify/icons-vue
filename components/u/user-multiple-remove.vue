<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unfsb6a4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unfsb6a4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:user-multiple-remove" /></template>
