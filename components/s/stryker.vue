<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcwz-8byp.css';
import '../../css/j/jz_z96ofw.css';
import '../../css/h/hx1pgx08q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="wcwz-8byp"><path class="jz_z96ofw"/><path class="hx1pgx08q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:stryker" /></template>
