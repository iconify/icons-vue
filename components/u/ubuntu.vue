<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vemjm8nfz.css';
import '../../css/i/iuvge1b8z.css';
import '../../css/h/hbl5-d2bc.css';
import '../../css/g/g-_-py2sf.css';
import '../../css/y/ygzgrcc7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<circle class="vemjm8nfz"/><circle class="iuvge1b8z"/><g id="SVGekoPYc2I"><circle class="hbl5-d2bc"/><path class="g-_-py2sf"/><circle class="ygzgrcc7j"/></g><use href="#SVGekoPYc2I" transform="rotate(120 50 50)"/><use href="#SVGekoPYc2I" transform="rotate(240 50 50)"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ubuntu" /></template>
