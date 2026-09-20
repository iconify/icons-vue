<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/y4ufzepjc.css';
import '../../css/t/tiigb8gda.css';
import '../../css/r/rdf4k-b5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="y4ufzepjc"/><path class="tiigb8gda"/><path class="rdf4k-b5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:message-dots-round-cross" /></template>
