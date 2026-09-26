<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhkxqfb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fhkxqfb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-left-outline" /></template>
