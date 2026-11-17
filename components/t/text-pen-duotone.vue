<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z5qy-bctl.css';
import '../../css/z/z9w1x66uv.css';
import '../../css/v/v5cvinb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z5qy-bctl"/><path class="z9w1x66uv"/><path class="v5cvinb2z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:text-pen-duotone" /></template>
