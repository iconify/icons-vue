<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp8jkl.css';
import '../../css/i/i7fxbk.css';
import '../../css/j/j-yyay.css';
import '../../css/g/glymdo.css';
import '../../css/b/botfzx.css';
import '../../css/s/so-from-52.css';
import '../../css/f/fill-to-1.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-to-2px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGzW4qcc1a"><path class="xp8jkl"/><circle class="i7fxbk j-yyay"/><circle class="glymdo i7fxbk"/></mask></defs><path mask="url(#SVGzW4qcc1a)" class="botfzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:pizza-filled" /></template>
