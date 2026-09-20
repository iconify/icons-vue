<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sng0m5e4g.css';
import '../../css/e/emnqjpbpk.css';
import '../../css/m/m8jecfmey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sng0m5e4g"/><path class="emnqjpbpk"/><path clip-rule="evenodd" class="m8jecfmey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:speaker-minimalistic-bold-duotone" /></template>
