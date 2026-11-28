<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz--dybeb.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dzkpl7bps.css';
import '../../css/p/p9wysibpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary zz--dybeb"/><g class="dt0cm9dhy primary"><path class="dzkpl7bps"/><path class="p9wysibpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:vote-duo" /></template>
