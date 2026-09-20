<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr6u22bfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gr6u22bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:text-bar-solid" /></template>
