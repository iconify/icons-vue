<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv8ko8b5d.css';
import '../../css/s/sttlk4byq.css';
import '../../css/m/mgxiggbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gv8ko8b5d"/><path class="sttlk4byq"/><path class="mgxiggbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:volume-mute-sharp" /></template>
