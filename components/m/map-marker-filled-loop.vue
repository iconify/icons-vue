<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6imhw.css';
import '../../css/x/xbw4tl.css';
import '../../css/b/botfzx.css';
import '../../css/s/so-from-48.css';
import '../../css/t/tr-7ecuqx.css';
import '../../css/f/fill-to-1.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-to-2_5px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGhmwRcbbQ"><path class="a6imhw"/><circle class="xbw4tl"/></mask></defs><path mask="url(#SVGhmwRcbbQ)" class="botfzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:map-marker-filled-loop" /></template>
