<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb4ow_bno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bb4ow_bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:sizing-solid" /></template>
