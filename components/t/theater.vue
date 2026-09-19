<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/m/m7vi1cvwd.css';
import '../../css/x/x5yo2db5t.css';
import '../../css/g/g8e6vqbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m7vi1cvwd"/><path class="x5yo2db5t"/><path class="g8e6vqbev"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:theater" /></template>
