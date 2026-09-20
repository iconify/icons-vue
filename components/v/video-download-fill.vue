<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg6rx7blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg6rx7blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:video-download-fill" /></template>
