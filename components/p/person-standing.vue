<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/l/lgf7rpbof.css';
import '../../css/g/gbyjw7b_q.css';
import '../../css/g/gx73n_bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="lgf7rpbof wm-shadow"/><path class="gbyjw7b_q wm-shadow"/><path class="gx73n_bub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:person-standing" /></template>
