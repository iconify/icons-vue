<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2bc8ac_f.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z_xu3_bfs.css';
import '../../css/p/py10k9b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGA9GA4JbJ" width="22" height="22" x="1" y="1" maskUnits="userSpaceOnUse" style="mask-type:luminance"><path class="s2bc8ac_f"/></mask><g mask="url(#SVGA9GA4JbJ)" class="ft5dv1b6b"><path class="z_xu3_bfs"/><path class="py10k9b2c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate-color:scale-horizontal" /></template>
