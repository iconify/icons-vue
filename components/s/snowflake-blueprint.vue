<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/d/d-b3ocbgq.css';
import '../../css/n/na1x6msij.css';
import '../../css/m/m7rn_ibfa.css';
import '../../css/m/mspcjjimr.css';
import '../../css/b/b_gxetb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="d-b3ocbgq wm-deco"/><path class="na1x6msij wm-deco"/><path class="m7rn_ibfa wm-k"/><path class="mspcjjimr wm-a"/><path class="b_gxetb0h wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:snowflake-blueprint" /></template>
