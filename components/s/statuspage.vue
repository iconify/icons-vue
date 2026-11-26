<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt7tskbwm.css';
import '../../css/o/ol788r1ej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="nt7tskbwm"/><path class="ol788r1ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:statuspage" /></template>
