<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzg1bwb1s.css';
import '../../css/v/vfddtzbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nzg1bwb1s"/><path class="vfddtzbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:terminal" /></template>
