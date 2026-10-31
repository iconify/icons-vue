<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/f/f6a-2rbfx.css';
import '../../css/e/eocdi3b5s.css';
import '../../css/l/lv22f_bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="f6a-2rbfx wm-shadow"/><path class="eocdi3b5s wm-shadow"/><path class="lv22f_bmy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:tornado" /></template>
