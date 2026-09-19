<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/k/km9at4bxk.css';
import '../../css/j/jhucqqbwo.css';
import '../../css/a/aodbtw1pq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="km9at4bxk"/><path class="jhucqqbwo"/><path class="aodbtw1pq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:quarantine-place-house-shield" /></template>
