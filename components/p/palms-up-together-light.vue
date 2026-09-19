<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t5l4pnwkh.css';
import '../../css/t/ttdh2_bas.css';
import '../../css/g/gs4ffiuvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="t5l4pnwkh"/><path class="ttdh2_bas"/><path class="gs4ffiuvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:palms-up-together-light" /></template>
