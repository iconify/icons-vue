<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/etj7zqhmh.css';
import '../../css/n/nwng0crdr.css';
import '../../css/a/a3uc20buk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="etj7zqhmh"/><path clip-rule="evenodd" class="nwng0crdr"/><path class="a3uc20buk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:treadmill-round-bold" /></template>
