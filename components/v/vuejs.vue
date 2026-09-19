<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaaxbibek.css';
import '../../css/h/h-b6q9b2h.css';
import '../../css/g/gueqvmrxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qaaxbibek"/><path class="h-b6q9b2h"/><path class="gueqvmrxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:vuejs" /></template>
