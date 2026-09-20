<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/v/vlyhtbbyo.css';
import '../../css/w/wyerq1-7y.css';
import '../../css/x/xffcndilr.css';
import '../../css/u/ur14wvsfk.css';
import '../../css/r/rvux61dlp.css';
import '../../css/o/omsnwu1iq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="vlyhtbbyo"/><path class="wyerq1-7y"/><path class="xffcndilr"/><path class="ur14wvsfk"/><path class="rvux61dlp"/><path class="omsnwu1iq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:newspaper-read-man" /></template>
