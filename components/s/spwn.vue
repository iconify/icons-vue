<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwc5kob9j.css';
import '../../css/n/na9-sph2f.css';
import '../../css/s/sq4561bvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g transform="translate(13.512 10.42)scale(.06153)"><circle class="uwc5kob9j"/><circle class="na9-sph2f"/><path class="sq4561bvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:spwn" /></template>
