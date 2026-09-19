<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1mdvbqre.css';
import '../../css/j/jh4i-mbro.css';
import '../../css/i/ipqn73b5n.css';
import '../../css/k/kc2lvibvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<circle class="e1mdvbqre"/><path class="jh4i-mbro"/><path class="ipqn73b5n"/><path class="kc2lvibvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="geo:turf-bezier" /></template>
