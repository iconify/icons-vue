<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/r/re_3czw2d.css';
import '../../css/h/hb5frye-n.css';
import '../../css/g/gnawts8ku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="re_3czw2d"/><path class="hb5frye-n"/><path class="gnawts8ku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:washing-machine" /></template>
