<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/d/dye8fz2in.css';
import '../../css/h/h0jbmubck.css';
import '../../css/t/tawp0wban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="dye8fz2in"/><path class="h0jbmubck"/><path class="tawp0wban"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:reminder" /></template>
