<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/p/p20adwbpg.css';
import '../../css/o/oua8bue4c.css';
import '../../css/c/c-hdtesmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p20adwbpg"/><path class="oua8bue4c"/><rect class="c-hdtesmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:paint-gun" /></template>
