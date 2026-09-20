<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7uinz_wv.css';
import '../../css/m/my4v-7bwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g7uinz_wv"/><path class="my4v-7bwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:riverside-fm" /></template>
