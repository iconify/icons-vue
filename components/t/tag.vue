<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp-d1-b9o.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/av3m8fbrw.css';
import '../../css/d/d3gjt8lcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGsDOZcc6q" class="hp-d1-b9o"/></defs><g class="ft5dv1b6b"><use href="#SVGsDOZcc6q"/><g class="av3m8fbrw"><use href="#SVGsDOZcc6q"/><path class="d3gjt8lcd"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:tag" /></template>
