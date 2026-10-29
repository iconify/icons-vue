<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/b/bt2s4pbvn.css';
import '../../css/r/rbzq4bjzv.css';
import '../../css/d/dabaijbqi.css';
import '../../css/g/go3ojebxo.css';
import '../../css/s/st_8ncf7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="bt2s4pbvn wm-deco"/><path class="rbzq4bjzv wm-deco"/><path class="dabaijbqi wm-k"/><path class="go3ojebxo wm-a"/><path class="st_8ncf7j wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sd-card-blueprint" /></template>
