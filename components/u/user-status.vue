<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/o/o9_d-n63m.css';
import '../../css/w/wkm6c6j9i.css';
import '../../css/f/fj697fbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o9_d-n63m"/><path class="wkm6c6j9i"/><path class="fj697fbfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:user-status" /></template>
