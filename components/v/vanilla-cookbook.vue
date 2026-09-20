<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv5fksbba.css';
import '../../css/b/bsakxhhri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rv5fksbba"/><path class="bsakxhhri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vanilla-cookbook" /></template>
