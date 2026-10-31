<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/p/pz7c98mqm.css';
import '../../css/y/ydgymnbxt.css';
import '../../css/f/ffzga1q9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="pz7c98mqm wm-shadow"/><path class="wm-shadow ydgymnbxt"/><path class="ffzga1q9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:person-swimming" /></template>
