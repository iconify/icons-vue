<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m7pevhgad.css';
import '../../css/r/rh2wlpewm.css';
import '../../css/a/akfaaw7bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="m7pevhgad"/><path class="rh2wlpewm"/><path class="akfaaw7bz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:rofl-light" /></template>
