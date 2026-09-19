<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwuxmlj9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwuxmlj9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:mobile-alt" /></template>
