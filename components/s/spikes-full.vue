<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr__c4rcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pr__c4rcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spikes-full" /></template>
