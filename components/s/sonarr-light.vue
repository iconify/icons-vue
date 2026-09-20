<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9481-llz.css';
import '../../css/k/ko8oeoczp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r9481-llz"/><path class="ko8oeoczp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sonarr-light" /></template>
