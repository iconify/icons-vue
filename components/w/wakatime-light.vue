<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pw3n31uic.css';
import '../../css/b/bww9v6dvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":340,"height":340};
const content = `<g class="ft5dv1b6b"><path class="pw3n31uic"/><path class="bww9v6dvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:wakatime-light" /></template>
