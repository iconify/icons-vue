<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/b0a7tkekm.css';
import '../../css/b/b946ibi6z.css';
import '../../css/m/mzqewjw4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b0a7tkekm"/><path class="b946ibi6z"/><path class="mzqewjw4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:real-estate-01" /></template>
