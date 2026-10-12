<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h0fqg75xv.css';
import '../../css/s/s1a2eew1e.css';
import '../../css/f/fz4n4bcix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h0fqg75xv"/><path class="s1a2eew1e"/><path clip-rule="evenodd" class="fz4n4bcix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-star-duotone" /></template>
