<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vhlh1hb6b.css';
import '../../css/m/mno1kzu5b.css';
import '../../css/d/didum-i0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vhlh1hb6b"/><path class="mno1kzu5b"/><path class="didum-i0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:queue" /></template>
