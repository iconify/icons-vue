<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0dfacccx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o0dfacccx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:megaphone-2-solid" /></template>
