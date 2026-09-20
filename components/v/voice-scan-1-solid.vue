<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp19n8hlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sp19n8hlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:voice-scan-1-solid" /></template>
