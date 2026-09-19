<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m27p55t_c.css';
import '../../css/g/gqu4bebvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="m27p55t_c"/><path class="gqu4bebvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:nasm" /></template>
