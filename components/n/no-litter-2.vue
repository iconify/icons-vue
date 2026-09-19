<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpva-4bbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpva-4bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:no-litter-2" /></template>
