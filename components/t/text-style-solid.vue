<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w40axwd7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w40axwd7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:text-style-solid" /></template>
