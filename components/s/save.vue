<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/u/uhlhzujjg.css';
import '../../css/p/pkwdlrb9z.css';
import '../../css/g/gyi273b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="uhlhzujjg"/><path class="pkwdlrb9z"/><path class="gyi273b3s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:save" /></template>
