<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/ygrj4yfdy.css';
import '../../css/v/vk-tonb9y.css';
import '../../css/r/rdxk35b9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ygrj4yfdy"/><path class="vk-tonb9y"/><path class="rdxk35b9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:pipette-duotone" /></template>
