<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/ym-uxxb9p.css';
import '../../css/a/aor1mmhyl.css';
import '../../css/t/tavu7dgmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ym-uxxb9p"/><path class="aor1mmhyl"/><path class="tavu7dgmz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:umbrella-duotone" /></template>
