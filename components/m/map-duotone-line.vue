<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ih9e1vb8h.css';
import '../../css/x/xg3h85bnw.css';
import '../../css/x/xbh224b0r.css';
import '../../css/e/edss2cc6j.css';
import '../../css/w/w49j0rbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGdf7dacXC"><g class="ft5dv1b6b"><path class="ih9e1vb8h"/><path class="xg3h85bnw"/><path class="xbh224b0r"/><circle class="edss2cc6j"/></g></mask></defs><path mask="url(#SVGdf7dacXC)" class="w49j0rbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:map-duotone-line" /></template>
