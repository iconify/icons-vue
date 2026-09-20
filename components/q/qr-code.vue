<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv65oib5o.css';
import '../../css/n/n7ab-r98n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pv65oib5o"/><path class="n7ab-r98n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:qr-code" /></template>
