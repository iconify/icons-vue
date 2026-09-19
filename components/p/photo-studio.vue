<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/r/r-qavsvxr.css';
import '../../css/q/qur47fbzu.css';
import '../../css/i/i01q7abel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="r-qavsvxr"/><path class="qur47fbzu"/><path class="i01q7abel"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:photo-studio" /></template>
