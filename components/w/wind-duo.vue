<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gkf7pdbgi.css';
import '../../css/v/v335rzk7y.css';
import '../../css/a/aaskxzbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="gkf7pdbgi wm-a"/><path class="v335rzk7y"/><path class="aaskxzbtv wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wind-duo" /></template>
