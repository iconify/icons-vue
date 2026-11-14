<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/etba-6bny.css';
import '../../css/r/r_k86acet.css';
import '../../css/o/o-geo2jre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="etba-6bny"/><path class="r_k86acet"/><path class="o-geo2jre"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:message-favourite-02" /></template>
