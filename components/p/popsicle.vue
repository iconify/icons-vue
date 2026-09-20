<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wlteh9bxn.css';
import '../../css/b/blhx95bup.css';
import '../../css/o/orzu1it2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wlteh9bxn"/><path class="blhx95bup"/><path class="orzu1it2s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:popsicle" /></template>
