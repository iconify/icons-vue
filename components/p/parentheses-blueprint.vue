<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/o/ow7qzrb3h.css';
import '../../css/i/ik09c_b2k.css';
import '../../css/m/m9_-f2byv.css';
import '../../css/b/b9dbb0e0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="ow7qzrb3h wm-deco"/><path class="ik09c_b2k wm-deco"/><path class="m9_-f2byv"/><path class="b9dbb0e0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:parentheses-blueprint" /></template>
