<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7wkc6bmm.css';
import '../../css/u/u0c79lbga.css';
import '../../css/j/jvytkl3_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":121,"height":121};
const content = `<circle class="w7wkc6bmm"/><path class="u0c79lbga"/><path class="jvytkl3_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vrs" /></template>
