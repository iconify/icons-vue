<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/podu248gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="podu248gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:timeline-event-minus" /></template>
