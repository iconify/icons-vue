<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swkylxb0c.css';
import '../../css/x/xnoj2lhrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="swkylxb0c"/><path class="xnoj2lhrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:right-arrow-curving-down" /></template>
