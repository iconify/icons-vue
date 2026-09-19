<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9h87yb9c.css';
import '../../css/j/jkn1k3bqn.css';
import '../../css/d/d6ao8lora.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="s9h87yb9c"><path clip-rule="evenodd" class="jkn1k3bqn"/><path class="d6ao8lora"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:map-marker" /></template>
