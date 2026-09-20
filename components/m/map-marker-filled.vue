<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_tayl.css';
import '../../css/x/xbw4tl.css';
import '../../css/b/botfzx.css';
import '../../css/s/so-from-48.css';
import '../../css/f/fill-to-1.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-to-2_5px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGG73SyevI"><path class="t_tayl"/><circle class="xbw4tl"/></mask></defs><path mask="url(#SVGG73SyevI)" class="botfzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:map-marker-filled" /></template>
