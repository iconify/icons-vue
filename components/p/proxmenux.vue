<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjejn750n.css';
import '../../css/i/ionc-bb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vjejn750n"/><path class="ionc-bb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proxmenux" /></template>
