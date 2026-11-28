<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfdide9pn.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/om8qxl02a.css';
import '../../css/j/jrqqhb3az.css';
import '../../css/u/uj4ngxb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfdide9pn secondary"/><g class="dt0cm9dhy primary"><path class="om8qxl02a"/><path class="jrqqhb3az"/><path class="uj4ngxb8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:zoom-in-duo" /></template>
