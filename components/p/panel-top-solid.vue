<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3i4eyd2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3i4eyd2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:panel-top-solid" /></template>
