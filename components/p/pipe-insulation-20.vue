<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz02lvbot.css';
import '../../css/z/z7r22xbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lz02lvbot"/><path class="z7r22xbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipe-insulation-20" /></template>
