<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dgznh9z6x.css';
import '../../css/i/iu0-ovbgw.css';
import '../../css/r/rvpalfbkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="dgznh9z6x"/><path class="iu0-ovbgw"/><path class="rvpalfbkp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:presentation" /></template>
