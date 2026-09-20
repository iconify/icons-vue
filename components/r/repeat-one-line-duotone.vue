<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/t/t1afujhin.css';
import '../../css/s/sec9xqbsa.css';
import '../../css/v/vny47hble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t1afujhin"/><path class="sec9xqbsa"/><path class="vny47hble"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:repeat-one-line-duotone" /></template>
