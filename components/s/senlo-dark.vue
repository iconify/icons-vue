<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idolizczw.css';
import '../../css/d/dhkr_wblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="idolizczw"/><path class="dhkr_wblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:senlo-dark" /></template>
