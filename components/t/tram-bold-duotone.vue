<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2v64kbha.css';
import '../../css/i/i-hsyrblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d2v64kbha"/><path class="i-hsyrblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tram-bold-duotone" /></template>
