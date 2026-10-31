<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovqg_nbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovqg_nbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:waveform-sparkle-round" /></template>
