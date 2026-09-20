<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsp-aobcy.css';
import '../../css/f/fbai653fp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":500,"height":500};
const content = `<path class="hsp-aobcy"/><path class="fbai653fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:vlang" /></template>
