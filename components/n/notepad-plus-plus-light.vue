<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6a_bmqya.css';
import '../../css/r/r5ot870ug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s6a_bmqya"/><path class="r5ot870ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:notepad-plus-plus-light" /></template>
