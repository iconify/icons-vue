<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rohbddizm.css';
import '../../css/f/fjrjp3bov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rohbddizm"/><circle transform="rotate(-88.939 82.069 29.398)scale(.99997)" class="fjrjp3bov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:pytorch" /></template>
