<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fccbu8b2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fccbu8b2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:numbers-4" /></template>
