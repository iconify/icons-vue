<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr7wbsbom.css';
import '../../css/x/xlp5pbcfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nr7wbsbom"/><path class="xlp5pbcfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:metis" /></template>
