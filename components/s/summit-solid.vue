<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4dvv9l9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q4dvv9l9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:summit-solid" /></template>
