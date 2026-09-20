<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/venf5ntdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="venf5ntdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:wilderness-hut-14" /></template>
