<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/ax9c4lghs.css';
import '../../css/s/shh2lmd7z.css';
import '../../css/k/k0aooyyum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ax9c4lghs"/><path clip-rule="evenodd" class="shh2lmd7z"/><path clip-rule="evenodd" class="k0aooyyum"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:store-bold" /></template>
