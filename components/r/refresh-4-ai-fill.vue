<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmf2di1ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmf2di1ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:refresh-4-ai-fill" /></template>
