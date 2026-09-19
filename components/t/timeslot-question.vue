<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3doeqbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2560,"height":1344};
const content = `<path class="n3doeqbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:timeslot-question" /></template>
