<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvsb-2b0n.css';
import '../../css/n/nbh4wzn0v.css';
import '../../css/g/gu86148fg.css';
import '../../css/e/ensolhbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hvsb-2b0n"/><path class="nbh4wzn0v"/><path class="gu86148fg"/><path class="ensolhbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wire-stripper-20-bold" /></template>
