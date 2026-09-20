<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_s7-nb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s_s7-nb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:radio-solid" /></template>
