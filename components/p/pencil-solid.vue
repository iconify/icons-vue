<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mte9jlnvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mte9jlnvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:pencil-solid" /></template>
