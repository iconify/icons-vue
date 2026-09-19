<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/myquthk1w.css';
import '../../css/q/q_4uk-b_w.css';
import '../../css/n/nuj67m2yh.css';
import '../../css/o/o1fuzks_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="myquthk1w"/><path class="q_4uk-b_w"/><path clip-rule="evenodd" class="nuj67m2yh"/><path class="o1fuzks_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sort-amount-down-outline" /></template>
