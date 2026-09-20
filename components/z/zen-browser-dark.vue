<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm9_3bbqh.css';
import '../../css/y/y-5x8pjfu.css';
import '../../css/f/fm6tes6gl.css';
import '../../css/b/bqublpl9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g clip-rule="evenodd" class="nm9_3bbqh"><path class="y-5x8pjfu"/><path class="fm6tes6gl"/><path class="bqublpl9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:zen-browser-dark" /></template>
