<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0vhp-jis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d0vhp-jis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:slightly-smiling-face-fill" /></template>
