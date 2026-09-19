<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuixw-bhr.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vboo6ubhn.css';
import '../../css/d/d2kvgvbvc.css';
import '../../css/o/o5v5dgu4m.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVG30fSr5dC" class="tuixw-bhr"/><mask id="SVGmuJ1AerM"><g class="ft5dv1b6b"><path class="vboo6ubhn"/><use href="#SVG30fSr5dC"/><use href="#SVG30fSr5dC" clip-rule="evenodd" class="d2kvgvbvc"/><path class="o5v5dgu4m"/></g></mask></defs><path mask="url(#SVGmuJ1AerM)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:steering-wheel" /></template>
