<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/i/i4sitdlur.css';
import '../../css/v/vca6n0zbn.css';
import '../../css/i/i1vbw2wll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="i4sitdlur"/><path class="vca6n0zbn"/><circle class="i1vbw2wll"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:sunset" /></template>
