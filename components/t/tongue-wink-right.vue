<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/y/ygh7ci8ga.css';
import '../../css/a/ayc2nrb8u.css';
import '../../css/a/ab8vmjhok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ygh7ci8ga"/><path class="ayc2nrb8u"/><path class="ab8vmjhok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tongue-wink-right" /></template>
