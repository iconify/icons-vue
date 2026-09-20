<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0cmkm9pe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0cmkm9pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:view-in-ar-filled" /></template>
