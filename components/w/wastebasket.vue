<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtfcmbcna.css';
import '../../css/r/rfp-f_hib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gtfcmbcna"/><path class="rfp-f_hib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:wastebasket" /></template>
