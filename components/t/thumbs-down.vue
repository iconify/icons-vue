<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/g/ga_sunbve.css';
import '../../css/v/v9_s8abew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect transform="rotate(180 21.25 16.8)" class="ga_sunbve"/><path class="v9_s8abew"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:thumbs-down" /></template>
