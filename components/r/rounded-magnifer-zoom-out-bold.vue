<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w9c06acrm.css';
import '../../css/k/kqrobaccw.css';
import '../../css/n/nkv2sfb4k.css';
import '../../css/w/w49j0rbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGzADSHeme"><g class="ft5dv1b6b"><path class="w9c06acrm"/><path clip-rule="evenodd" class="kqrobaccw"/><path clip-rule="evenodd" class="nkv2sfb4k"/></g></mask></defs><path mask="url(#SVGzADSHeme)" class="w49j0rbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifer-zoom-out-bold" /></template>
