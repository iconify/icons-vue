<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3v3pf.css';
import '../../css/t/t5pxry.css';
import '../../css/j/jv25_c.css';
import '../../css/b/botfzx.css';
import '../../css/k/k55jyf.css';
import '../../css/u/ufposl.css';
import '../../css/t/tyi0xw.css';
import '../../css/s/so-from-48.css';
import '../../css/f/fill-to-1.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-to-2_5px.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGTlOlfdAj"><path class="e3v3pf t5pxry"/><circle class="jv25_c"/></mask></defs><path mask="url(#SVGTlOlfdAj)" class="botfzx"/><path class="k55jyf t5pxry ufposl"/><path class="t5pxry tyi0xw ufposl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:map-marker-remove-filled" /></template>
