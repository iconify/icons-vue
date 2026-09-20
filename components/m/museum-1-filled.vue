<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni_p_obvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ni_p_obvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:museum-1-filled" /></template>
