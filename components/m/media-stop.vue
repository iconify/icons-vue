<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwskzebwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iwskzebwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:media-stop" /></template>
