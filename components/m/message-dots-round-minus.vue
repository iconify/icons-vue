<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/y4ufzepjc.css';
import '../../css/i/i6_rhfb3t.css';
import '../../css/t/tiigb8gda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="y4ufzepjc"/><path class="i6_rhfb3t"/><path class="tiigb8gda"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:message-dots-round-minus" /></template>
