<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/w/ws0weable.css';
import '../../css/p/pdmaa-4wh.css';
import '../../css/j/jcyhgg-5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ws0weable"/><path class="pdmaa-4wh"/><path class="jcyhgg-5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mouse-12" /></template>
