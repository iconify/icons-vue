<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vayc-0b-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vayc-0b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:sword-attack-solid" /></template>
