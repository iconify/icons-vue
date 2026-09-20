<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss3a5qvmd.css';
import '../../css/u/u_xkcvb2m.css';
import '../../css/d/dckmfac-n.css';
import '../../css/k/kdd976b_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2000,"height":2000};
const content = `<defs><clipPath id="SVGfGwZpcDD" clipPathUnits="userSpaceOnUse"><path class="ss3a5qvmd"/></clipPath></defs><g clip-path="url(#SVGfGwZpcDD)" transform="matrix(1.33333 0 0 -1.33333 0 2000)"><path class="u_xkcvb2m"/><path class="dckmfac-n"/><path class="kdd976b_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:pre-commit" /></template>
