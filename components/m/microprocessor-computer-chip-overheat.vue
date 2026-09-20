<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qmyruqboo.css';
import '../../css/i/iqvxyvbht.css';
import '../../css/x/xfrwc6b-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qmyruqboo"/><path class="iqvxyvbht"/><path class="xfrwc6b-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:microprocessor-computer-chip-overheat" /></template>
