<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/g/gwg-y3bus.css';
import '../../css/t/t22me5f7h.css';
import '../../css/o/ost3o95wd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gwg-y3bus"/><path class="t22me5f7h"/><path class="ost3o95wd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-line-duotone" /></template>
