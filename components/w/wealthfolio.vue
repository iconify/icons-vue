<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0nm-3j1m.css';
import '../../css/o/o4qm4qbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="v0nm-3j1m"/><path class="o4qm4qbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wealthfolio" /></template>
