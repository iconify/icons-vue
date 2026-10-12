<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/packvzbps.css';
import '../../css/n/nex76-inj.css';
import '../../css/t/tz--tdn4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="packvzbps"/><path class="nex76-inj"/><path class="tz--tdn4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-pen-duotone" /></template>
