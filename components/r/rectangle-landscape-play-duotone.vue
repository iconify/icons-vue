<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kt86k5xbe.css';
import '../../css/i/i3jxg4b6g.css';
import '../../css/u/ugd6x5rii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kt86k5xbe"/><path class="i3jxg4b6g"/><path clip-rule="evenodd" class="ugd6x5rii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:rectangle-landscape-play-duotone" /></template>
