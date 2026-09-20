<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-bo3ibyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v-bo3ibyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:typo3-light" /></template>
