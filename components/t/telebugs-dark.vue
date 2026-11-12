<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swgihk1vm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="swgihk1vm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:telebugs-dark" /></template>
