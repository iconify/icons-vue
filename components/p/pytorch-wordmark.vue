<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff_zigbzi.css';
import '../../css/r/r46vxebie.css';
import '../../css/e/et996hggo.css';
import '../../css/o/os8b0uf2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ff_zigbzi"/><circle class="r46vxebie"/><path class="et996hggo"/><path class="os8b0uf2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:pytorch-wordmark" /></template>
