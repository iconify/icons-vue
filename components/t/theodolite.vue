<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abyirpbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="abyirpbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:theodolite" /></template>
