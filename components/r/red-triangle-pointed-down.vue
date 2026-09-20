<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at6mhmmvf.css';
import '../../css/r/r258pibsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="at6mhmmvf"/><path class="r258pibsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:red-triangle-pointed-down" /></template>
