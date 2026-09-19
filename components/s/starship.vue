<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmqd7lb1z.css';
import '../../css/s/s6x7m9trg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><mask id="SVGcVHSkeyt" maskUnits="userSpaceOnUse"><circle class="nmqd7lb1z"/></mask></defs><path mask="url(#SVGcVHSkeyt)" class="s6x7m9trg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:starship" /></template>
