<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x-64p5ubv.css';
import '../../css/m/md286fbip.css';
import '../../css/b/bdw0vhb6r.css';
import '../../css/w/w40ak50xy.css';
import '../../css/w/w_01-_bnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="x-64p5ubv"/><g class="md286fbip"><path class="bdw0vhb6r"/><path class="w40ak50xy"/><path class="w_01-_bnw"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:tusd" /></template>
