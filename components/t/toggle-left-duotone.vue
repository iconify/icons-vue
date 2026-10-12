<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dswk5-x-u.css';
import '../../css/m/mrknojtdi.css';
import '../../css/v/vzuisubco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dswk5-x-u"/><path class="mrknojtdi"/><path clip-rule="evenodd" class="vzuisubco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:toggle-left-duotone" /></template>
