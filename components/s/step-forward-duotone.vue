<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bbm58abcy.css';
import '../../css/p/p9eupo9br.css';
import '../../css/s/smehn_blx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bbm58abcy"/><path class="p9eupo9br"/><path class="smehn_blx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:step-forward-duotone" /></template>
