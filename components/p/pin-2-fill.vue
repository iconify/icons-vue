<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu4r2kb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uu4r2kb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pin-2-fill" /></template>
