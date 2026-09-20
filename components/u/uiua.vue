<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sury3b-zu.css';
import '../../css/w/w_iz3k4gm.css';
import '../../css/c/cjn1osbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<g class="sury3b-zu"><path class="w_iz3k4gm"/><path class="cjn1osbna"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:uiua" /></template>
