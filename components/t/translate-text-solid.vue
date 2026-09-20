<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekyi5ob7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ekyi5ob7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:translate-text-solid" /></template>
