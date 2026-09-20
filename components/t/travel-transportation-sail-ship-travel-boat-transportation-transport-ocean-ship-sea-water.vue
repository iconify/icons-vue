<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn_bipmzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="kn_bipmzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:travel-transportation-sail-ship-travel-boat-transportation-transport-ocean-ship-sea-water" /></template>
