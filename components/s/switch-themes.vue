<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/g/gopxn0bty.css';
import '../../css/t/t-9twgrad.css';
import '../../css/m/mfdkm_-jy.css';
import '../../css/n/n9w1ojbeo.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGWpwvuGAr"><g class="hv130ab-t"><path clip-rule="evenodd" class="gopxn0bty"/><path class="t-9twgrad"/><path class="mfdkm_-jy"/><path class="n9w1ojbeo"/></g></mask></defs><path mask="url(#SVGWpwvuGAr)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:switch-themes" /></template>
