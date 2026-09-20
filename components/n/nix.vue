<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au6clhbxu.css';
import '../../css/c/cpvng1bhd.css';
import '../../css/n/nbpor1b9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":500,"height":500};
const content = `<g class="au6clhbxu"><path class="cpvng1bhd"/><path class="nbpor1b9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:nix" /></template>
