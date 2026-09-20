<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7mfpjuoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u7mfpjuoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notebook-minimalistic-outline" /></template>
