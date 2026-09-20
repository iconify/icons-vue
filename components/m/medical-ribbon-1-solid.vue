<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-knf-gad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c-knf-gad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:medical-ribbon-1-solid" /></template>
