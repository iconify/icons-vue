<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6ojhhb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c6ojhhb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:pen-1-solid" /></template>
